[source](https://juejin.im/post/59093b1fa0bb9f006517b906)
先讲下call apply

bind 方法会创建一个新函数， 调用时， 第一个参数作为它运行时的this, 之后的一序列参数将会在传递的实参前传入作为它的参数。

与call 不同， 它是返回在函数 

1. 返回一个函数
2. 可以传入参数

1.js

- 传参， 可以多次传。。。。
  2.js

- 构造函数效果的模拟实现
  一个绑定函数也能使用new操作符创建对象：这种行为就像把原函数当成构造器。提供的this值被忽略，同时调用时的参数被提供给摸拟函数

4.js