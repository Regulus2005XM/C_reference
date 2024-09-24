### 常量(constant)变量(variable)类型

```c
typedef int newint;

//C语言无boolean类型(可以引入<stdbool.h>(C99))
char mychar = 'A';	//字符类型，存储ASCII码，占用1byte(存储整数，可用范围内的整数赋值)
//C语言无Spring类型(使用字符数组)
//末尾空字符\0(null character)，用于标记字符串结束，ASCII码为0

//char fate = 'FATE'; -> char fate = 'E';
int myint = 42;		//整数类型，占用4byte，约+-2*10^9
short myshort = 2;	//占用2byte，-32768~32767，
long mylong = 1729;	//占用4byte
long long  //占用8byte(约+-9e+18)

unsigned short myunsigned = 65535;	//无符号类型0~65535
const float pi = 3.14;				//常量

float myfloat;		//4byte(6位小数)
double mydouble;	//8byte(15位小数)
long double my_ld	//12byte(18位小数)
//浮点常量示例：(3.14) (.2) (100.) (3e5) (.8E-5)

_Bool = true/false //布尔类型(C99)
_Complex //复数 (C99)
_Imaginary //虚数 (C99)

sizeof(leixing); //返回byte数目
```
