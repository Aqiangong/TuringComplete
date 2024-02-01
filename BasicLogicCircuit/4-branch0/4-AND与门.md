## 与门特性

| input0 | input1 | output |
| :----: | :----: | :----: |
|   0    |   0    |   0    |
|   0    |   1    |   0    |
|   1    |   0    |   0    |
|   1    |   1    |   1    |

## 解决方案

看出来了嘛？AND和NAND的特性刚好相反。所以我们可以轻易地想到，给NAND的output加一个NOT即可，我们手中可用的部件刚好可以简洁地实现。

![image-20240201145514551](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20240201145514551.png)