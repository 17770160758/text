# text
C基础
#include "stdafx.h"
#include "string.h"
#define MAX 10


//enum Sex
//{
//	MALE,
//	FEMALE,
//	SECRET
//};


//int Add (int x,int y)
//{
//	int z=0;
//	z=x+y;
//	return z;
//
//}


int _tmain(int argc, _TCHAR* argv[])
{
	//sizeof 类型空间大小计算 int  char float double
	/*int a;
	printf ("%d ",sizeof(a));*/
	char b;
	printf ("%c ",sizeof(b));


	//赋值操作符 
	//-= += *= /= &= |= ^= %=



	//操作符
	//int a=5%2;
	//printf ("%d\n",a);//算术操作符 + - * / %
	//int a=1;
	//int b=a<<2;
	//printf ("%d\n",b);//移位操作符 <<左移    >>右移
	//int a=4,b=6;
	//int c=a^b;
	//printf ("%d\n",c);//&按位与 |按位或 ^按位异或






	//数组
	/*int arr[10]={1,2,3,4,5,6,7,8,9,10};
	char ch[5]={'a','b','c','d','f'};
	int i=0;
	while(i<10)
	{
		
		printf ("%d ",i);
		i++;
	}*/



	//函数
	/*int num1=10,num2=20;
	int sum=0;
	sum=Add(num1,num2);
	printf ("sum=%d\n",sum);*/





	//while()循环
	/*int line=0;
	while(line<=20000)
	{
		printf ("牛老板是蠢猪?:%d\n",line);
		line++;
	}
	if(line>=20000)
	printf ("是的\n");*/





	//if语句
	/*int input=0;
	printf ("你期末成绩多少分？\n");
	printf ("刚好及格吗？还是90分以上 >:");
	scanf("%d",&input);
	if(input>=90)
		printf ("90分以上",input);
	else if(input>=80)
		printf ("80分以上",input);
	else if(input>=70)
		printf ("70分以上",input);
	else if(input>=60)
		printf ("60分以上",input);
	else
		printf ("不及格",input);*/



	/*转义字符
	printf ("%c",'\4');
	printf ("%c",'\x4');*/



	//字符串   ASCII编码 
	/*char arr[]="abc";
	printf ("%s\n",arr);
	char arr1[]={'a','b','c','\0'};
	printf ("%s\n",arr1);//'\0'作为结束标志
	printf("%d\n",strlen("c:\text\32\text.c"));//string-length计算字符长度*/


	/*int num1,num2;
	int sum=0;
	scanf("%d%d",&num1,&num2);
	sum=num1+num2;
	printf("sum=%d\n",sum);*/



	/*#define 定义的常量
	int  arr[MAX]={0};
	printf("%d\n",MAX);*/


	/*Enum 枚举常量
	printf("%d\n",MALE);//0	
	printf("%d\n",FEMALE);//1
	printf("%d\n",SECRET);//2*/




	/*const--修饰常变量
	const int num=4;
	printf("num=%d\n",num);
	 //num=8;
	//printf("num=%d\n",num);*/
	return 0;
}

