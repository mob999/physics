# Oscillations
## 1.[**SHM**](#1) 简谐运动
## 2.[**Expression Medthods of SHM**](#2) 简谐运动的表示方法
## 3.[**Energy in SHM**](#3) 简谐运动的能量
## 4.[**Pendulums**](#4) 钟摆
## 5.[**Resonance**](#5) 共振
## 6.[**Superpostion of Oscillations**](#6) 震荡叠加 
***
## 1.**SHM** 简谐运动 <span id="1"></span>

### 简谐运动的特征：
* 可以用简单的正弦或余弦函数表示
* 复原力必须作用在物体上
* 加速度必须和位移成正比
***
### 简谐运动公式：
* $x=Acos(\omega t+\phi)$
* A:振幅
  * $-A<=x<=A$
* $\omega$:角速度
  * $\omega=2\pi f$
  * $f=\frac{\omega}{2\pi}$
  * $T=\frac{1}{f}=\frac{2\pi}{\omega}$
  * 对弹簧振子：
    * $\omega=\sqrt{\frac{k}{m}}$
    * $T=\frac{2\pi}{\omega}=2\pi\sqrt{\frac{m}{k}}$
    * $f=\frac{1}{T}=\frac{1}{2\pi}\sqrt{\frac{k}{m}}$
* $\phi$:初相
  * 对两同频率的简谐振动，相位差等于初相差
* $\omega t+\phi$:相位
***
### 简谐运动的速度
* $v(t)=-\omega Asin(\omega t + \phi)=\omega Acos(\omega t + \phi + \frac{\pi}{2})$
* 范围：$[-\omega A,\omega A]$
* $v(t)$在$x(t)$前$\frac{\pi}{2}$
### 简谐运动的加速度
* $a(t)=-{\omega}^2Acos(\omega t+\phi)={\omega}^2Acos(\omega t+\phi+\pi)$
***
## 2.**Expression Methods of SHM** 简谐运动的表示法 <span id="2"></span>
### 分析法
### 画图法
### 匀速圆周运动（旋转矢量法）
* 作匀速转动的矢量$\overrightarrow{A}，其端点P在x轴上的投影P’的运动是SHM（逆时针）$
***
## 3.**Energy in SHM** 简谐运动的能量 <spam id="3"></span>
* $E=K+U=\frac{1}{2}mv^2+\frac{1}{2}kx^2=\frac{1}{2}kA^2$
* $v(x)=\plusmn\sqrt{\frac{k}{m}(A^2-x^2)}$
* $v_{max}=\sqrt{\frac{k}{m}}A=\omega A$
***
## 4.**Pendulums** 钟摆 <span id="4"></span>
### 单摆
* 恢复力：$F=-mgsin\theta$
* 对于很小的角：$F\approx-mg\theta$
* 对于很小的位移，单摆的运动是简谐运动
* $k=\frac{mg}{L},\omega=\sqrt{\frac{g}{L}},T=2\pi\sqrt{\frac{L}{g}}$
### 复摆
* $\gamma=-mghsin\theta$
* 对于很小的角：$F\approx-mg\theta,\gamma = -mgh\theta$
* $T=\frac{2\pi}{\omega}=2\pi\sqrt{\frac{I}{mgh}}$
***
## 5.**Resonance** 共振
### 1.阻尼振动
* 阻力$\Overrightarrow{F_d}=-bv$, $b$:阻尼常量
* $m\frac{d^2 x}{dt^2}+b\frac{dx}{dt}+kx=0$
* $x=Ae^{-bt/2m}cos(\omega't+\phi)$
* $\omega'=\sqrt{\frac{k}{m}-\frac{b^2}{4m^2}}$
* $f=\frac{\omega'}{2\pi}=\frac{1}{2\pi}\sqrt{\frac{k}{m}-\frac{b^2}{4m^2}}$
* $\alpha=\frac{b}{2m}表示振动减为0的快慢$
* 