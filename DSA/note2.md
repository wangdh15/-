## 数据结构与算法(二)
## 王道烩
## 2018.9.7

### 查找

![](./images/64.png)

![](./images/65.png)

#### 折半查找

如果顺序表有序,可以使用折半查找.

![](./images/66.png)

![](./images/67.png)

![](./images/68.png)

![](./images/69.png)

#### 二叉搜索树

二叉搜索树节点的删除:
如果待删除节点的左右子树都不空,那么可以用这个待删除节点的中序遍历的前驱或者后继来替换这个节点.

##### 二叉搜索树的旋转

![](./images/70.png)

![](./images/71.png)

### 散列

散列是利用散列函数将关键字集合映射到某个地址集合.

![](./images/72.png)

散列技术的两个部分是:散列函数和冲突处理.

![](./images/73.png)

![](./images/74.png)

![](./images/75.png)

![](./images/76.png)

![](./images/77.png)

### 排序

![](./images/78.png)

- 冒泡排序: 每一趟使一个元素就位.
- 插入排序:每一步将一个待排序的对象按照关键码的大小,插入到前面已经有序的对象的合适位置上.

![](./images/79.png)

- 选择排序:从未排序的中选出最小的放在合适的位置

![](./images/80.png)

#### 快排

![](./images/81.png)

![](./images/82.png)

![](./images/83.png)

![](./images/84.png)

#### 归并排序

先分成两个字表,分别使其有序,然后再合并.

![](./images/85.png)

![](./images/86.png)

![](./images/87.png)

