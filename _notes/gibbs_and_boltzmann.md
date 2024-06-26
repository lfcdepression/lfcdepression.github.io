# 吉布斯统计和玻尔兹曼统计
## 玻尔兹曼方法

## 吉布斯方法


## 平衡态的概念
相空间$\boldsymbol{X}$，$\mu_x$代表$\boldsymbol{X}$上的概率测度，$T_t(x)$代表从$x$开始的$t$时间后的系统状态，通常$T_t(x)$是确定的，但有时候在一些系统中动力学演化是一个随机过程$\{Z_t\}$（比如Ising模型）

吉布斯统计方法中研究对象是一个系综，遵循相同的方程但是处于不同的状态中，系综通过概率密度$\rho(x,t),x\in \boldsymbol{X}$描述，反映了在$t$时刻，从$\boldsymbol{X}$的某个部分系综中随机选择系统状态的概率。相空间中求平均值的方法是

$$\bar{f}(t)=\int_Xf(x,t)\rho(x,t)dx.$$

吉布斯熵是

$$S_G[\rho]=-k\int_X\rho(x,t)\log[\rho(x,t)]dx,$$

如果系综分布与时间无关，那么根据刘维尔定理我们有$\rho(x,t)=\rho(x)$，在吉布斯方法中，平衡是系综的一个基本性质。如果分布是平衡的并且在给定约束下有最大的熵，那么系综是平衡的。
