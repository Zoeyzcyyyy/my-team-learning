# 傅立叶神经算子
  神经网络的经典发展主要集中在学习有限维欧几里得空间之间的映射。最近，这已被推广到学习函数空间之间映射的神经算子。傅立叶神经算子的提出来自[Fourier Neural Operator for Parametric Partial Differential Equations](https://arxiv.org/abs/2010.08895)，通过在傅里叶空间中直接对积分核进行参数化，制定了一个新的神经算子。文中对Burgers方程、Darcy流和Navier-Stokes方程进行了实验。傅里叶神经算子是第一个以ML为基础的方法，成功地对湍流进行了zero-shot超分辨率建模。与传统的PDE求解器相比，它的速度高三个数量级（训练过程也称为offline过程，需要花费比较长的时间，但是已经训练好用于online预测速度很快。可以类比计算器，做计算器需要花费比手算一道题更长的时间，但是计算器做好之后进行大计算量的计算时效率高于手算）。

  傅立叶神经算子的作者此后又发表了[Fourier Neural Operator with Learned Deformations for PDEs on General Geometries](https://arxiv.org/pdf/2207.05209v1.pdf). 本文提出了Geo-FNO，将输入（物理）域（可能是不规则的）变形为一个具有均匀网格的潜在空间。FNO模型与FFT被应用于潜在空间，由此产生的Geo-FNO模型既具有FFT的计算效率，又具有处理任意几何形状的灵活性。Geo-FNO在输入格式方面也很灵活，包括点云、网格和设计参数。本项目可以尝试用傅立叶神经算子求解复杂区域的波动方程。
