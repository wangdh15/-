## 通信与网络
## 王道烩 
## 2018.9.8

网络的分层架构

- 应用层
- 表示层
- 会话层
- 传输层
- 网络层
- 链路层
- 物理层

### 课程主要内容

- 信息论基础
- 信源与信道编码
- 数字调制与解调
- 多址与复接
- 路由与交换
- 流控与队列管理

### 绪论与信息论基础

![](./images/1.png)

通信中的基础问题:

- 通信的资源
- 通信的失真

信息:能够消除不确定性的东西.小概率时间蕴含的信息量大

![](./images/2.png)

![](./images/3.png)

![](./images/4.png)

![](./images/5.png)

![](./images/6.png)

![](./images/7.png)

![](./images/8.png)

![](./images/9.png)

若两个随机变量相互独立,那么这两个的互信息为零.
若两个随机变量相等,则条件熵为0.

![](./images/10.png)

![](./images/11.png)

![](./images/12.png)

![](./images/13.png)

![](./images/14.png)

微分熵是对连续型变量相对不确定性的一种描述.

![](./images/15.png)

![](./images/16.png)

![](./images/17.png)

### 压缩编码理论

无损压缩:输入数字序列输出数字序列.
有损压缩:输入模拟信号(连续时间,连续幅值),输出数字序列.

![](./images/18.png)

![](./images/19.png)

![](./images/20.png)

带通抽样定理

![](./images/21.png)

![](./images/22.png)

![](./images/23.png)

![](./images/24.png)

![](./images/25.png)

![](./images/26.png)

![](./images/27.png)

![](./images/28.png)

![](./images/29.png)

![](./images/30.png)

均匀量化的问题:对具有不同概率权重的区间一视同仁,没有考虑概率密度对量化噪声的影响.


为了解决,可以对经常出现的区域使用较细的颗粒度进行量化,不经常出现的区域使用较粗的颗粒度进行量化.

![](./images/31.png)

![](./images/32.png)

增量调制:

![](./images/33.png)

但是如果变化过于大,可能会发生过载.这个时候可以通过使用自适应增量的方法.信号变换缓慢的时候,采用小的增量,变化大的时候采用大的增量.

### 数字基带传输

![](./images/34.png)

![](./images/35.png)

![](./images/36.png)

格雷码能够使得相邻符号出错时,二进制比特只查一位.

![](./images/36.png)

![](./images/37.png)

![](./images/38.png)

![](./images/39.png)

![](./images/40.png)

![](./images/41.png)

![](./images/42.png)

![](./images/43.png)

![](./images/44.png)

![](./images/45.png)

如果没有线谱,表示均值为零.

### 最佳接受

![](./images/46.png)

![](./images/47.png)

![](./images/48.png)

![](./images/49.png)

![](./images/50.png)

![](./images/51.png)

![](./images/52.png)

![](./images/53.png)

![](./images/54.png)

![](./images/55.png)

![](./images/56.png)

![](./images/57.png)

![](./images/58.png)

![](./images/59.png)

![](./images/60.png)

![](./images/61.png)

![](./images/62.png)

![](./images/63.png)

![](./images/64.png)

![](./images/65.png)

![](./images/66.png)

![](./images/67.png)

![](./images/68.png)

![](./images/69.png)

![](./images/70.png)

### 判决与差错

![](./images/71.png)

![](./images/72.png)

![](./images/73.png)

![](./images/74.png)

![](./images/75.png)

![](./images/76.png)

![](./images/77.png)

![](./images/78.png)

![](./images/79.png)

![](./images/80.png)

![](./images/81.png)

![](./images/88.png)

![](./images/89.png)

![](./images/90.png)

![](./images/91.png)

![](./images/92.png)

![](./images/93.png)

