1. 扩展教材P17例子2.1，定义表2.1（见P12）中所描述的所有类型的变量，并观察其所占内存空间的字节数（注：程序文件命名为P17_2_1.c）。

2. 完成教材P31习题2中的一、3和一、4，并将其编译运行，以测试你所写的结果是否正确（注：程序文件分别命名为P31_1_3.c和P31_1_4.c）。

3. 完成教材P31习题2中的二、4（注：请写出完整的可编译运行的程序，并多次修改变量x、a、b、c的值，以测试你所写出的表达式是否正确；程序文件分别命名为P31_2_4_1.c和P31_2_4_2.c）。

4. 理解前置自增/自减操作符与后置自增/自减操作符的异同（注：无须写程序）。

5. 阅读[The C Programming Language](https://github.com/njnucsta/C2018FALL/blob/master/book/TCPL_2rd_EN.pdf)一书2.9节，初步理解各种位运算操作符，及其使用技巧（注：无须写程序）。

6. 补充阅读：[Bitwise Operation]( https://en.wikipedia.org/wiki/Bitwise_operation)（英文的，慢慢看）（注：无须写程序）。

7. 补充阅读：[git简明教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)（中文的，别紧张）（注：无须写程序）。

8. 在如下程序中，去掉注释，在TODO的位置写一个表达式，这个表达式的作用是判断一个整数的奇偶性。使得当n为奇数时，flag为1；当n为偶数时，flag为0。编译运行，并多次修改n的值，以测试你所写的表达式是否正确（注：程序文件命名为parity.c；提示：使用三目运算符或位运算）。
```c
#include <stdio.h>
int main()
{
    int n = 10;
    int flag = /* TODO */;
    printf("%d\n", flag);
    return 0;
}
```
9. 补充练习：完成[The C Programming Language](https://github.com/njnucsta/C2018FALL/blob/master/book/TCPL_2rd_EN.pdf)一书Exercise2-6,2-7,2-8。（注：程序文件分别命名为tcpl_2_6.c，tcpl_2_7.c，tcpl_2_8.c）。

10. 在如下程序中，去掉注释，在TODO的位置写一些代码，做到能够交换a与b的数值。例如，若输入的a和b分别是3和5，那么两条printf语句的输出应当分别是：
```
a = 3, b = 5
a = 5, b = 3
```
（注：程序文件命名为swap.c；提示：分别采用临时变量与位运算的方式来完成）。
```c
#include <stdio.h>
int main()
{
    int a, b;
    scanf("%d%d", &a, &b);
    printf("a = %d, b = %d\n", a, b);
    /* TODO */
    printf("a = %d, b = %d\n", a, b);
    return 0;
}
```

注：作业提交到自己仓库的`19180xxx/20181009`目录下。截止日期：`2018.10.16-00:00:00`（零点）。
