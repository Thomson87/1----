#define _CRT_SECURE__NO_WARNINGS 1
//包含一个叫stdio.h的文件
//std-标准 standard input output
#include <stdio.h>

int main()//主函数-程序的入口-main有且只有一个
//{
//	//这里完成任务
//	//在屏幕上输入hello world
//	//函数-print function - printf - 打印函数
//	//库函数-C语言本身提供给我们使用的函数
//	//别人的东西-打招呼
//	//#include
//	printf("hello world\n"); // \n换行
//	return 0;
//}

//int是整型的意思
//main前面的int表示main函数调用返回一个整形值
//int main()
//return 0;//返回 0；
//这种写法是过时的写法
//void main()


//char -字符类型
//%d - 打印整形o
//%c - 打印字符
//%f - 打印浮点数字-打印小数
//%p - 以地址形式打印
//%x - 打印16进制数字
//%o 。。。
{
	//char ch = 'A';//内存
	//printf("%c\n", ch); //%c -- 打印字符格式的数据

	//short int - 短整型
	//int - 整型
	//int age = 20;
	//printf("%d\n", age); //%d -- 打印整形十进制数据

	//long 长整型
	//short int ch = 32767;
	//printf("%d\n" ,ch);
	//return 0;

	//float ch = 5.9999; //float -- 打印单精度浮点数浮点数
	//printf("%f\n", ch);

	//double ch = 3.14; //double -- 双精度浮点数
	//printf("%lf", ch);

	//大小
	//年龄 20
	//short age = 20;	//向内存申请16个bit位，用来存放20		
	//float weight = 94.6f; //向内存申请4个字节，存放小数
	
	//printf("%d\n", sizeof(char));        //bit - 比特位（最小单位）
	//printf("%d\n", sizeof(short));       //byte - 字节 = 8 bit
	//printf("%d\n", sizeof(int));         //kb = 1024 byte
	//printf("%d\n", sizeof(long));        //mb = 1024 kb
	//printf("%d\n", sizeof(long long));
	//printf("%d\n", sizeof(float));  
	//printf("%d\n", sizeof(double));
	//90min
	// 123 十进制数字                 // 010 二进制数字         //101 （001 >010 >011 >100 >101）
	// 1*10^2 + 2*10^1 + 3*10^0       // 0*2^2 + 1*2^1 + 0*2^0  //1*2^2 + 0*2^1 + 1*2^0
	// 100+20+3                       // 0+2+0                  //4+0+1=5
    
	//3位数能表达的最多数字 = 10^3（包括000） 二进制同理：111 = 2^3 = 8



	return 0;
	//基础知识 打印的数据类型 及大小 2进制

}# 1----
