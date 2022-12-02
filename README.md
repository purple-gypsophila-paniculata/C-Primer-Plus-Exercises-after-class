# C-Primer-Plus-Exercises-after-class
这仅仅是我学习C语言的时候的书后的课后习题
课后习题33页
#include<stdio.h>
void jolly();//第四题需要的函数
void deny();

void br();//第五题需要的函数
void ic();

//第七小题需要函数
void smile();
void a();

//第八小题
void one_three();
void two();
int main(void)
{   
	//第一小题打印
	printf("野原新之助\n 野原\n 新之助\n");    //第一题实验题干
	printf("Gustav Mahler\n");  //正式打印，第一次
	printf("Gustav\n Mahler\n");  //第二次打印内容
	printf("Gustav \n");  //第三次打印
	printf(" Mahler\n");  //第四次打印

	printf("我叫野原新之助，家在埼玉县\n");  //第二小题，打印姓名和地址

	//第三小题，将年龄换算成天数
	int y ;
	int d;
	y = 19;
	d = y * 365;
	printf("I am  %d years old,which means %d days\n",y,d);

	//第四小题
	jolly();
	jolly();
	jolly();
	deny();

	//第五小题
	br();    ic();
	ic();
	br();



	//第六小题
	int toes,toes2,toes3; //创造整型变量toes
	toes = 10;  //为toes赋值10
	toes2 = 10 * 10;
	toes3 = 10 + 10;
	printf("toes等于%d\n toes的平方等于%d\n toes的两倍等于%d\n",toes ,toes2,toes3);

	//第七小题
	smile(); smile(); a();
	smile(); a();
	a();

	//第八小题
	printf("starting now\n");
	one_three();

	return 0;
}
//给上面函数类似于赋值
void jolly()
{
	printf("For he's a jolly good fellow!\n");
}
void deny()
{
	printf("Which nobody can deny!\n");
}
void br()
{
	printf("Brazil,Russia");
}
void ic()
{
	printf("India,China\n");
}
void smile()
{
	printf("smile!");
}
void a()
{
	printf("smile!\n");
}
void one_three()
{
	printf("one\n ");
	two();
	printf("three\n");
}

void two()
{
	printf("two\n");
}

