## 题目：求圆圈中最后剩下的数字

题目理解还是有点难度的，开始一直没搞清楚什么意思。举个例子：由 0 1 2 3 4 构成的环。从数字0开始每次删除第3个数字，则删除的前四个数字依次是2，0，4，1因此最后剩下的数字是3。也就是讲删除一个节点之后，那么下一轮的删除的过程开始的节点就是本次删除节点的下一个节点。比如说第一次删除了 2，那么开始下一轮删除过程的开始节点就是 3.以此类推。

![](http://ww2.sinaimg.cn/large/b10d1ea5jw1f7iqhwertuj20jb0e6abt.jpg)

还是看看动态规划的概念呗。