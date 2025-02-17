# 相关工作整理
## [Seismic wave propagation and inversion with Neural Operators](https://www.semanticscholar.org/paper/Seismic-wave-propagation-and-inversion-with-Neural-Yang-Gao/00c26749f30eac748cfb24ec22fe4fef0ac2b7e4)
   地震波的传播构成了地震学研究的大多数方面的基础，然而解决波方程是一个主要的计算负担，影响了研究的进展。每当速度结构或震源位置受到扰动时，就必须进行新的模拟。本文用二维声波方程来证明傅立叶神经算子适用于地震层析成像，使用反向传播自动微分来计算与速度结构有关的波场梯度。所开发的程序比使用传统的数值方法进行全波形反演要快一个数量级。本文同一作者的其他两个求解波动方程的相关工作
   [Rapid Seismic Waveform Modeling and Inversion with Universal Neural Operators](https://www.semanticscholar.org/paper/Rapid-Seismic-Waveform-Modeling-and-Inversion-with-Yang-Gao/91e7a1a2a1be79da3da5a003b685247dc399f079)、[Accelerated full seismic waveform modeling and inversion with U-shaped Neural Operators](https://www.semanticscholar.org/paper/ede492756350216667403ae3b289e1b2f03d7568)
## [Physics-guided deep learning using Fourier neural operators for solving the acoustic VTI wave equation](https://www.earthdoc.org/content/papers/10.3997/2214-4609.202113304)
  PINNs(物理信息神经网络,单个方程求解的神经网络方法)只能解决声波方程的单一实例，现实中往往需要针对每个不同的地下模型和频率重新进行训练。傅里叶神经算子可以用一组网络配置和参数解决多个模型和频率的声波方程。不过，这种方法需要大量的数据，而这些数据是很难获得的，也很昂贵。在这里，我们提出了一种方法，将PINNs与傅里叶神经算子结合起来，学习声波方程的解算子，而不需要任何训练数据。本文提出了两个数值例子，证明了所提方法在频域中准确有效地模拟声波场的能力。

## [Learning the elastic wave equation with Fourier Neural Operators](https://geoconvention.com/wp-content/uploads/abstracts/2022/73317-learning-the-elastic-wave-equation-with-fourier-ne.pdf)
  傅里叶神经算子(FNO)首次被训练来学习弹性波方程的合成训练数据集。
