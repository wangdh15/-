## 信号与系统
## 王道烩
## 2018.9.5

### 课程大概

![](./images/1.png)

信号与系统是关于信号和系统的基本概念和基本分析方法的课程.

![](./images/2.png)

![](./images/3.png)

![](./images/4.png)

#### 单位冲击信号

![](./images/5.png)

![](./images/6.png)

实际信号都是实信号,认为构成复信号后分析更加方便.

可逆系统:不同输入不同响应.

稳定系统:输入有界输出有界.(BIBO)

线性系统:满足叠加性与齐次性.

时不变系统:输入延时,输出波形不变,只是时间推迟.

线性时不变系统具有微分性和积分特性.可以由线性和时不变特性推出.

因果系统:某一个时刻的响应只与这一时刻之前的输入有关.

![](./images/7.png)

#### 系统的数学模型表示

![](./images/8.png)

![](./images/9.png)

![](./images/10.png)

![](./images/11.png)

然后根据初始条件确定待定的系数.

在判断初始状态是否发生跳变的时候,可以使用物理的方法,也可以使用数学的方法.数学的方法只要是delta函数匹配法.方程两端奇异函数平衡.

![](./images/12.png)

![](./images/13.png)

![](./images/14.png)

![](./images/15.png)

复指数函数是LTI系统的特征函数.

![](./images/16.png)

#### 卷积

将输入信号分解成一系列的冲击信号的叠加,然后由线性时不变性,可以将输出看做一系列输出的叠加.然后利用卷积进行加权叠加就可以得到任意输入的输出.

![](./images/17.png)

复指数函数是LTI系统的特征函数.输入是复指数函数,输出仍是相同指数的复指数函数.只是幅度和相位发生变化.

![](./images/18.png)

![](./images/19.png)

卷积的微积分性质

### 傅里叶变换

![](./images/20.png)

![](./images/21.png)

冲击函数的傅里叶变换是1.

![](./images/22.png)

时域压缩,频域扩展,时域扩展,频域压缩.
时域压缩,能量减小,各频率分量减小.

![](./images/23.png)

![](./images/24.png)

![](./images/25.png)

![](./images/26.png)

### 周期信号的傅里叶变换

![](./images/27.png)

![](./images/28.png)

![](./images/29.png)

### 抽样

![](./images/30.png)

![](./images/31.png)

![](./images/32.png)

![](./images/33.png)

![](./images/34.png)

### 拉普拉斯变换

![](./images/35.png)

![](./images/36.png)

![](./images/37.png)

![](./images/38.png)

![](./images/39.png)

![](./images/40.png)

![](./images/41.png)

![](./images/42.png)

![](./images/43.png)

![](./images/44.png)

### 传递函数分析

![](./images/45.png)

![](./images/46.png)

![](./images/47.png)

![](./images/48.png)

![](./images/49.png)

![](./images/50.png)

![](./images/51.png)

![](./images/52.png)

#### 全通函数与最小相移函数

![](./images/53.png)

全通函数不影响幅频响应,只影响相频响应.一般在系统中做相位矫正.

![](./images/54.png)

零点全部在左半平面或jw轴上的为最小相移系统.非最小相移系统可以表示为最小相移系统与全通函数的级联.

![](./images/55.png)

![](./images/56.png)

#### 双边拉普拉斯变换

![](./images/57.png)

![](./images/58.png)

![](./images/59.png)

### 傅里叶变换的应用

![](./images/60.png)

![](./images/61.png)

#### 无失真传输

线性失真:没有多出频率分量
非线性失真:有新的频率分量出现.

线性失真包括幅度失真和相位失真.

无失真值得是希望响应和激励形状相同,幅度可以改变,延时可增加.

![](./images/62.png)

![](./images/63.png)

![](./images/64.png)

![](./images/65.png)

![](./images/66.png)

![](./images/67.png)

![](./images/68.png)

![](./images/69.png)

吉布斯现象可以理解为用阶跃信号去和sa函数做卷积,卷到一半的时候,为0.5,但是在sa函数右半部分第一个零点之前,总会有一部分是大于零,积分就会出现过冲.


#### 系统的物理可实现性

![](./images/70.png)

![](./images/71.png)

paley-Wiener准则是判别可实现性的必要条件不是充分条件,只约束了幅度特性,没约束相位特性.实际上只有多项式类型的函数和双曲函数满足佩里-维纳准则.

##### 希尔伯特变换

![](./images/72.png)

![](./images/73.png)

由上述推导可知,因果是实信号的傅里叶变换的实部和虚部之间是存在制约关系的.

### 调制与解调

目的:

- 传输更远
- 天线尺寸
- 多路复用
- 零点漂移?

抑制载波调幅:和与余弦函数想乘.
调幅:

![](./images/74.png)

解调过程是包罗检测电路,可以通过二极管电容电阻来实现.

![](./images/75.png)

#### 单边带

![](./images/76.png)

可以节省带宽

![](./images/77.png)
  
![](./images/78.png)

解调频的时候,先对信号求导,然后用包络检测电路检测出包络,.或者直接使用建平器或者鉴相器直接提取出频率和相位的变化.

![](./images/79.png)

### 抽样信号回复原始信号

![](./images/80.png)

![](./images/81.png)

![](./images/82.png)

![](./images/83.png)

![](./images/84.png)

![](./images/85.png)

![](./images/86.png)

