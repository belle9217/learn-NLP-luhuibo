
## 我的sci笔记


```markdown

为什么要用numpy

    Python中提供了list容器，可以当作数组使用。但列表中的元素可以是任何对象，因此列表中保存的是对象的指针，这样一来，为了保存一个简单的列表[1,2,3]。就需要三个指针和三个整数对象。对于数值运算来说，这种结构显然不够高效。
    Python虽然也提供了array模块，但其只支持一维数组，不支持多维数组(在TensorFlow里面偏向于矩阵理解)，也没有各种运算函数。因而不适合数值运算。
    NumPy的出现弥补了这些不足。

（——摘自张若愚的《Python科学计算》）


————————————————
版权声明：本文为CSDN博主「furuit」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/fu6543210/article/details/83240024
- 数组创建
- 数组的常用函数
```