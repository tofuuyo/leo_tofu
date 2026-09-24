# 开始学习
## *my first.cpp的内容*
- 所含元素
1.注释：//
2.预处理器编译指令：#include 
3.函数头：int main()
4.编译指令：using namespace
5.函数体：用{}扩起来
6.使用C++的cout工具显示消息的语句
7.结束main()函数的语句
 
 ## *变量和常量*
- 内存空间起名操作
	1.变量创建的语法：数据类型		变量名	= 		变量初始值;		![输入图片说明](/imgs/2026-09-24/KOA9qhJ9qp08ungP.png)
	2.【1】#define 宏常量		定义在文件上方表示一个常量
	> #define 常量名	常量值

	【2】const修饰的变量     通常在在变量定义前加const改为常量
	>const 数据类型   常量名  =   常量值;

## *关键字*
- 变量命名时不能用关键字
- 标识符命名规则：不能是关键字，只用字母、数字和下划线，第一个字符必须为字母，标识符字母区分大小写

## *数据类型*（给变量分配合适的内存空间）
### 1.整型

| 数据类型| 占用空间 | 取值范围 |
| :----- | :------: | -----: |
| short   | 2字节   | -2^15 ~ 2^15-1 |
| int | 4字节 | -2^31 ~ 2^31-1 |
| long |win为4字节，lin为4字节（32位）和8字节（64位）  |-2^31 ~ 2^31-1  |
| longlong |8字节  |-2^63 ~ 2^63-1  |

### 2.实型（用于表示小数）
- 单精度float，双精度double。两者表示的有效数字范围不同。

| 数据类型| 占用空间 | 取值范围 |
| :-----       | :------:       | -----:       |
|float|4字节|7位有效数字|
|double|8字节|15~16位有效数字|
- 科学计数法：3e2 = 3 * 10^2





<!--stackedit_data:
eyJoaXN0b3J5IjpbMzcwNTE4MTE4LDE2OTg0NTIwNzcsMTE0Mj
A1MjA4MywtODQxMzkxNTU1LDUxNjI4MjM0MywtMTc1NzkzMzQy
NSwtNzQxMDI1NDQsLTEwNzczNjYyODYsMTM3MjU0MjY1NywtMT
I4MjUxNTc2Ml19
-->