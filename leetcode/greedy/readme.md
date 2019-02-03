[source](https://time.geekbang.org/column/article/73188)
[~1的计算步骤](https://www.cnblogs.com/moqiutao/p/6275483.html)

贪心 分治  回溯算法 动态规化。 思想，不是具体算法， 具体的算法和编码等。

## greedy algorithm 
霍夫曼编码 Prim 和 Kruskal 最小生成树算法， Dijkstra 单源最短路径算法。
如何利用贪心算法来实现对数据压缩编码， 有效节省数据存储空间的。

100Kg 物品的背包， 5种豆子， 每种的总量和总价值都各不相同， 

按单价由高王低依次来装就好了。 借助的是贪心算法。

### 看到这类问题， 要联想到贪心算法， 限制值， 期望值， 选出几个数据， 在满足限制值的情况下， 期望值更大。 
限制值，  重要不超过100kg,  期望值是物品的总价值。  重量不超过100Kg, 并且总价值最大。

### 是否可以用贪心算法解决

### 是否最优
  贪心不一定最优。 前面的选择会影响后面的选择。

1. 分糖果
  m 个糖果和n 个孩子。 m < n 
  s1, s2, s3, ..., sm
  需求 g1, g2, g3,...., 


### candy 
给定一个偶数长度的数组， 其中不同的数字代表着不同种类的糖果， 每一个数字代表一个糖果。 你需要将这些糖果平均分给一个弟弟和一个妹妹。 返回妹妹可以获得的最大糖果的种类数。
偶数 平分
candies = [1,1,2,2,3,3]
3
[1,2,3]妹妹 

candies = [1,1,2,3]
[2,3]

1. 让妹妹获得所有的种类
2. 妹妹获得种类的上限是？记住candies 要平均分配
3. 数据结构
4. 哈希？




## 讲法

运算符分为七类 赋值运算符  算术运算符  比较运算符  逻辑运算符  条件运算符  位移运算符  字符串运算符

- 移位运算
  将指定的值按二进制位移动，为移位运算。
  6  二进制这 110 
  6<<2  两个小于号， 即将6的二进制数110向左移两位，后补零。
  11000   24
  6>>2 两个大于号， 即将6的二进制数110向右移两位，即 11 为3
  右移数据意义是右移一位相当于除2， 移n位相当于除以n。

- 取反操作
  ! 可以做取反操作
  ~ 可以做按位取反, 处理二进制数据时候的非， ~~就是再转回来， 利用两个按位取反的符号，可以进行类型转换，为数字符号。
  ~1 = -2
  1 的二进制     00000001
  按位取反       11111110
  除符号位取反    10000001  
  未位加1取其补码 10000010  正数就减1
  换回十进制      -2
  ~~true == 1
  ~~false == 0
  ~~（10/3） = 3

- map 
  es6 新的数据结构
  是一种更完善的Hash结构实现。 相比Object 优点是， 键的范围不限于字符串， 种种类型的值都可以键。
 

其实这是个典型的贪心算法， 是一种常用的算法思想

- 问题的模式  限制值 平分 candies.length /2  和期望值 种类
- 贪心算法解决  对限制值同等贡献量时， 对期望值贡献最大的数据
- 产生的结果最优





