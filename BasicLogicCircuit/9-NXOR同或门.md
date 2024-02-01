## 同或门特性

| input0 | input1 | output |
| :----: | :----: | :----: |
|   0    |   0    |   1    |
|   0    |   1    |   0    |
|   1    |   0    |   0    |
|   1    |   1    |   1    |

## 解决方案

从真值表中可以看出，NXOR的output与XOR的output相反，所以在XOR的output后加一个NOT即可实现。

![image-20240201155135362](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20240201155135362.png)