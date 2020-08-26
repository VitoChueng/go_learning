### 程序结构和执行
#### 信息的表示和处理
二值信号处理。无符号编码基于传统的二进制表示法，表示大于或等于0的数字。 补码编码是表示有符号整数的最常见的方式，有符号整数就是可以为正或者为负的数字。 浮点数编码是表示实数的科学记数法的以2为基数的版本。<br>
计算机的表示法是用有限数量的位来对一个数字编码，因此可能某些运算会溢出。整数运算和浮点数运算会有不同的数学属性是因为他们处理数字表示有限性的方式不同--整数的表示虽然只能编码一个相对较小的数值范围，但是这种表示是精确的；而浮点数虽然可以编码一个较大的数值范围，但是这种表示只是近似的。看起来，运算浮点数只能获取一个范围值。<br>

#### 信息储存
大多数计算机使用8位的块或者字节(byte)，作为最小可寻址的内存单位，而不是访问内存中单独的位。机器级程序将内存视为一个非常大的字节数组，称为虚拟内存。内存中的每个字节都由一个唯一的数字来标识，称为它的地址，所有可能地址的集合就称为虚拟地址空间。这个虚拟地址空间只是一个展现给机器级程序的概念性影像。DRAM、闪存、磁盘存储器、特殊硬件和操作系统软件结合起来，为程序提供一个看上去统一的字节数组。<br>

每个程序对象都可以简单地视为一个字节块，而程序本身就是一个字节序列。<br>

指针: 值与类型。值表示某个对象的位置，类型表示那个位置上所存储对象的类型。<br>

##### 十六进制表示法
每个十六进制的数字都对16个值中的一个进行了编码。0-15。<br>
