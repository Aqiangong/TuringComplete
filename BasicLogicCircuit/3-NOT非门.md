## 非门特性

| 输入 | 输出 |
| :--: | :--: |
|  0   |  1   |
|  1   |  0   |

## 解决方案

因为本关非门是单输入单输出的，但是我们目前能够利用的部件只有前一关的NAND，NAND**是两个输入一个输出**的，回想NAND特性，**当input0和input1全为0时，output为1** ；**当input0和input1全为1时，output为0**。发现了嘛？这就是我们要实现的NOT，所以我们可以把输入的信号同时送给NAND的两个输入端，即模拟两个input，且input0和input1相同，这时候NAND就会给出我们想要的答案。

![image-20240201144948058](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20240201144948058.png)