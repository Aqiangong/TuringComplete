## 或门特性

| input0 | input1 | output |
| :----: | :----: | :----: |
|   0    |   0    |   0    |
|   0    |   1    |   1    |
|   1    |   0    |   1    |
|   1    |   1    |   1    |

## 解决方案

有了或非门的经验，想必这一关就没有任何难度了，在NOR的基础上再加一个NOT？当然可以，但是硬件资源不但增加，而且浪费，想一想，我们在实现NOR的时候，在NAND的output后加了一个NOT，将其去掉即可。

![image-20240201151109939](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20240201151109939.png)