# Datastructre & Algorithm in Java

Java实现的数据结构&算法，只需要用IDE导入即可。

🔧环境和工具
------
  1. Java8 & Maven
  2. Idea or Eclipse

# 📖 目录
------
## 线
### 字符串 

[String的 `==` 和 `equals`]()

### 链表 
[删除链表重复元素]()

[链表排序]() 
  
[链表环儿]()

### 栈 
栈的实现
  
记录存储容量和索引的栈
  
能获取最小值的栈
  
汉诺塔
  
栈全测试

### 队列 
  
队列实现
  
两栈实现队列
  
队列全测试

### 查找 
二分查找 [二分查找测试]

### 排序 
冒泡排序

归并排序

快速排序
  
选择排序
  
插入排序
  
插入优化排序
  
排序全测试

### 树
树 

树的前序，中序，后续遍历搜索 [遍历搜索测试]

二叉树判断 [二叉树判断测试] 

平衡树判断 [平衡树判断测试] 

查找两节点共同祖先 共同祖先测试 

数组变二叉查找树

## 图
两种基本搜索:[图的广度优先和深度优先搜索] [广度优先和深度优先搜索测试]

图的路径:[有向图路径判断] [有向图路径判断测试])

## 并发
多线程基础 [线程实现之继承Thread] [线程实现之实现Runnable]

多线程应用 

实现锁的ATM取款与存款

哲学家就餐问题之会死锁的哲学家

死锁哲学家测试
  
哲学家就餐问题之不会死锁的哲学家
  
[同步对象][同步线程] [Lock Condition转账] [synchronized wait转账] 

线程池
### IO 

BIO服务端

BIO客户端

伪NIO服务端

NIO服务端
  
NIO客户端
  
AIO服务端
  
AIO客户端

Netty 

## 设计模式
五种单例模式


# Q & A
什么人适合这个项目？

处于打基础的黄金时间的在校大学生，正在准备找工作的求职者，自我提高的在职者等。

为什么用Java？

使用人数多，年龄分布广，不管是工龄10+的程序员还是在校大学生，都可以驾驭。

为什么准备大量的测试代码？

三个原因：第一，证明算法是对的，不管是作者自己实现的，还是摘录他人的。第二，方便做性能测试，只需要控制入口大小就可以测出性能，用于比较。第三，方便用户debug，对于很多人来说如果要理解程序的执行流程，最好的方式就是debug。

# TODO
* 字符串: `KMP`算法
* 树: `红黑树`，`B树`,`trie树`,`哈希树`,`蒙特卡洛搜索树`
* 算法: `贪心`, `DP(动态规划)`