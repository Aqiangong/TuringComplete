## 或非门特性

| input0 | input1 | output |
| :----: | :----: | :----: |
|   0    |   0    |   1    |
|   0    |   1    |   0    |
|   1    |   0    |   0    |
|   1    |   1    |   0    |

## 解决方案

我们能够利用的部件有哪些？NAND和NOT。

回顾NAND，当00时，为1；当01时，为1；当10时，为1；当11时，为0。与NOR特性相比，NOR的01/10/00/11对应NAND的10/01/11/00取反。所以NAND的output需要有个NOT。input的关系，也是对应input取反。所以如下：

![image-20240201145941204](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20240201145941204.png)