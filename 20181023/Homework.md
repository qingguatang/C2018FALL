1.实现教材P81例4.13，并思考：判断一个整数n是否为素数时，是否一定需要判断n不能被2~(n-1)之间的任何一个整数整除？给出一个优化的方法（注：程序命名为P81_4_13.c）。

2.求`a^b mod c`,其中a^b为a的b次方，mod为取余。写一个程序，读入整型数据a、b、c，输出`a^b mod c`的值。保证你的程序当a、b的值很大时，依然是正确的（注：程序命名为pow_mod.c）。

3.完成PTA平台中的[805](https://pintia.cn/problem-sets/14/problems/805)一题，将你的程序在线提交，直到正确为止（注：程序命名为3.c）。

4.完成PTA平台中的[801](https://pintia.cn/problem-sets/14/problems/801)一题，将你的程序在线提交，直到正确为止（注：程序命名为4.c）。

5.完成PTA平台中的[806](https://pintia.cn/problem-sets/14/problems/806)一题，将你的程序在线提交，直到正确为止（注：程序命名为5.c）。

6.完成PTA平台中的[789](https://pintia.cn/problem-sets/14/problems/789)一题，将你的程序在线提交，直到正确为止（注：程序命名为6.c）。

7.重新考虑第2题，你是否有办法将计算`a^b mod c`的方法优化，使之计算得更快呢？（注：程序命名为7.c）。

下面给出一个可以观测程序执行时间的模板。你可以将其应用到你的优化后的代码中。前后对比，判断优化后的程序是否真的快了，快了多少。当然，由于程序的执行时间很短，也许难以观测到差别，你可以运行同一段代码多次，以求多次的执行时间总和，作为考量依据。
```c
#include <stdio.h>
#include <time.h>
int main() {
	clock_t start_clock, end_clock;
	double elapsed_time;
	int i;
	start_clock = clock();
	for (i=1; i<=1000000000; ++i)
		/*
		* // TODO: insert your code here
		*/
	end_clock = clock();
	elapsed_time = (double)(end_clock - start_clock)/ CLOCKS_PER_SEC;
	printf("%.6lf",elapsed_time);
	return 0;
}
```
8.编写一个完整的程序，打印出杨辉三角形。控制好输出格式，使得你的输出做到对齐、美观（注：程序命名为8.c）。

9.编写一个完整的程序，读入N（N<100,000），随机生成N个范围在[1,N]的整数，并存入数组arr中。分别输出该数组中的最大值与最大值所对应的数组下标（若有多个相同的最大值，输出最小的数组下标）、最小值与最小值所对应的数组下标（若有多个相同的最小值，输出最小的数组下标）、和、平均值、方差、标准差（注：程序命名为9.c）。

注：作业提交到自己仓库的`19180xxx/20181023`目录下。截止日期：`2018.10.30-00:00:00`（零点）。
