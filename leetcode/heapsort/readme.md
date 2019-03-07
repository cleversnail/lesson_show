[source](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/heap-sort)

基于比较的排序算法。可以被认为是一种改良版本的选择排序。将输入划分为排好序和未排序。

[source](https://juejin.im/post/5b3608336fb9a00e765e8ed4)

二叉树
满二叉树
完全二叉树

堆
堆分类

左子树， 右子树 有左右次序， 不能随意颠倒

满二叉树 深度为K,  
完全二叉树

Heap 特殊的数据结构的统称。 可以被看作一棵树的数组对象
binary heap 

堆排序 就是利用堆进行排序的方法
待排序的数组构成一个大顶堆。 最大值是堆顶的根节点。
将它移走， 其实就是将其与堆数组的未层元素交换， 此是未尾就是最大值， 然后将
剩余的n-1个元素又重新构造成堆 次大值

Max-Heapify  大顶堆的性质， 

堆排序可以是一种利用堆的概念来排序的选择排序。时间复杂度为O(nlogn)



堆是完全二叉树， 每个结点的值大于或等于其左右孩子结点的值， 大顶堆；
每个结点的值都小于或等于其左右孩子结点的值， 小顶堆

堆排序是一种利用堆的概念来排序的选择排序。 O(nlogn);


