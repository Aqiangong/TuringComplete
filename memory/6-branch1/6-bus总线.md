## 要求

![image-20240205145835693](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20240205145835693.png)

![image-20240205145850137](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20240205145850137.png)

## 解决方案

思路很简单，按照要求走就行，首先我们要明确的是，两个输入端是同时给出输入的，所以我们不能假定同一时刻钟只有一个输入有效而将其合并，所以我们应该使用开关来选择使用哪个输入，此时我们使用了一组（2个）8位开关，这一组开关的启用端是0号输入；同理，选择到输出到的目的端口，两个输出端也是同时有效的，我们通过另一组（2个）8位开关，来选择输出到哪个端口，这组开关的启用端是1号输入。

因为使用了开关，所以一些导线是可以合并的如下图。

![image-20240205145823944](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20240205145823944.png)