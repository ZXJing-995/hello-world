# hello-world
初入门C语言
#include<stdio.h>
int main();
{
 int input=0;
 printf（"hello world");
 return 0;
 }
 英文输入法
.c源文件
.h头文件
基本框架
#include<stdio.h>
int main();
//主函数-程序的入口- 有且仅有一个
{
 return 0；
}
int 整形
main前面的int表示函数调用返回一个整型值
目标文件.obj
可执行文件.exe
字节-计算机中的单位
bit--比特位
byte-字节
一个字节=八个比特位的大小
变量：局部变量，全局变量
main内称为局部变量
main外称为全局变量
局部变量和全局变量尽量不要相同，相同时优先选择局部变量
编译器的预处理以#为开头可嵌套
编译器处理：文件包含，宏定义，条件编译
文件包含：#include.<stdio.h>
宏定义：#define.名称，内容
区分判断编译和解释的方法是看需要执行的次数。编译只需要执行一次，之后再运行不需要重新编译。而解释执行的程序在每次运行时都要重新被解释。此题中程序每次运行都需要仿真器的帮助，所以应该属于解释执行
#include<stdio.h>
int
main0();
{
printf("你好\n");
return0;
}
