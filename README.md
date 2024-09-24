# C_reference
C语言的一些基础知识，用来查询与复习
---

### 内容
---
### 基础HelloWorld程序示例

```c
#include <stdio.h> //用此方式引用头文件
int main()	//从主函数开始
{
  printf("Hello World!");
  return 0;		//函数具有返回值
}
```

### 头文件

```c
#define _CRT_SECURE_NO_WARNINGS//用vs时不得不品鉴的一环，非微软IDE请忽略

#include<assert.h>//诊断库
#include <ctype.h>//字符处理库
#include <string.h>//字符串库
#include <stdio.h>//I/O输入输出库
#include <stdlib.h>//基本函数库
#include <math.h>//数学库
#include <limits.h>//整数与字符宏库
#include <float.h>//浮点宏库
#include <time.h>//时间与随机数库
```

### 宏定义

```c
#define MAX 1024

#define Conn(x,y) x##y //连接
#define ToChar(x) #@x //转字符
#define ToString(x) #x //转字符串
//不定参数的方法，暂无
```
位bit(Binary Digits) = 0/1<br />
字节byte = 8 bit<br />
字word = 8/16/32/64 bit<br />

1 KB(Kilobyte) = 1024 B<br />
1 MB(Megabyte) = 1024 KB<br />
1 GB(Gigabyte) = 1024 MB<br />
1 TB(Trillionbyte) = 1024 GB<br />
1 PB(Petabyte) = 1024 TB<br />
EB ZB YB BB
