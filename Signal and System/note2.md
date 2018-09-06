## 信号与系统(二)
## 王道烩
## 2018.9.6

### 信号分析

![](./images/87.png)

![](./images/88.png)

定义了內积的线性矢量空间称为內积空间.

![](./images/89.png)

![](./images/90.png)

![](./images/91.png)

![](./images/92.png)  

![](./images/93.png)

![](./images/94.png)

### 相关

研究两个信号的相似程度.

能量信号:能量有限的信号.
功率信号:能量无限但功率有限的信号.

![](./images/95.png)

![](./images/96.png)

相关直接移位求积分,但是卷积向反褶,然后移位求积分.

自相关函数是偶函数.R(0)为最大值/周期信号的自相关函数还是周期信号,周期不变.自相关安徽省农户丢失了相位信息.

![](./images/97.png)

自相关函数的傅里叶变换是功率频密度.

![](./images/98.png)

![](./images/99.png)

![](./images/100.png)

![](./images/101.png)

![](./images/102.png)

### 离散系统分析

![](./images/103.png)

![](./images/104.png)

![](./images/105.png)

![](./images/106.png)

![](./images/107.png)

![](./images/108.png)

#### 解卷积

![](./images/109.png)

### Z变换

![](./images/120.png)

![](./images/121.png)

![](./images/122.png)

![](./images/123.png)

![](./images/124.png)

### 逆Z变换

- 部分分式分解
- 幂级数展开
- 围线积分法(流数法)

![](./images/125.png)

![](./images/126.png)

![](./images/127.png)

![](./images/128.png)

![](./images/129.png)

![](./images/130.png)

![](./images/131.png)

![](./images/132.png)

![](./images/133.png)

![](./images/134.png)

![](./images/135.png)

![](./images/136.png)

![](./images/137.png)

![](./images/138.png)

### 数字滤波器

![](./images/139.png)

![](./images/140.png)

![](./images/141.png)

### 信号流图

![](./images/142.png)

![](./images/143.png)

![](./images/144.png)

![](./images/145.png)

![](./images/146.png)

![](./images/147.png)

### 状态空间

以前研究的都是输出和输入之间的关系,状态空间通过定义一些独立的状态,然后将写出状态转移方程和输出方程.两个方程的自变量都是状态和输入.状态转移方程一般是微分当成组,输出方程是状态的线性组合以及输入的线性组合.

![](./images/148.png)

![](./images/149.png)

![](./images/150.png)

同一个系统,若留图形式不同,则状态变量选择不同,所以ABCD矩阵也不同.

![](./images/151.png)

![](./images/152.png)

![](./images/153.png)

可以对状态进行线性变换,然后取出状态之间的耦合性.

![](./images/154.png)

![](./images/155.png)

![](./images/156.png)

![](./images/157.png)

![](./images/158.png)

![](./images/159.png)

![](./images/160.png)

![](./images/161.png)

