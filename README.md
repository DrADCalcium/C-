# C-
# C语言第二节

***

## 特点

语言简洁，表达能力强，易于理解

可直接访问__物理地址__

> 只有32个关键字，9种控制语句
> 
> 数据构造能力强
> 
> 运算符丰富
> 
> 程序书写格式自由

语言生成的代码质量高

可移植性好

***

## 编译

![编译原理](https://github.com/DrADCalcium/C-/blob/main/%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86.png?raw=true "编译原理")


***

__第一个程序Hello World__

```C
#include <stdio.h>

int main()
{
    printf("Hello World!");
    return 0;
}
```

***

__计算一个数的平方__

```C
#include <stdio.h>/*包含stdio.h（预处理指令）
.h头文件  std标准
stdio = standard input output*/

#include <stdlib.h>
/*包含stdlib.h（预处理指令）
lib库*/

int main()
{
    float a,b;//定义两个变量a,b（类型float  浮点数）
    a = 5.2;//将5.2赋值给a
    b = a*a;//讲a^2赋值给b
    printf( "%f\n", b );//，调用输出函数printf，以format格式方式打印b
    printf( "Hello World!\n" )
    return 0;//返回语句，main函数结果
}

```

<kbd> \n </kbd>表示换行符

<kbd> {} </kbd>程序体外壳

！！！__写程序时每执行完一步务必加<kbd> ; </kbd>__

***

__输入两个数，输出其中单位大数__（return实例）

```C
int max( int x,y )//编写max函数
{
    int z;
    if( x > y )
        z = x;
    else
        z = y;
    return(z);
}
void main()//主函数
{
    int a,b,c;
    scanf("%d, %d",&a, &b);
    c = max(a,b);//调用max函数，求a和b中大者
    printf("max = %d\n, c")
}


```



__注意分行！便于理解__

***
![好习惯](https://github.com/DrADCalcium/C-/blob/main/good%20habits.png?raw=true "好习惯")
![结论1](https://github.com/DrADCalcium/C-/blob/main/conclusion%201.png?raw=true "结论1")
