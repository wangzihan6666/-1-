初学c++

#include <stdio.h>   
int main()                                                                                                                   
{

  char c1,c2,c3,c4,c5;

  
  scanf("%c%c%c%c%c",&c1,&c2,&c3,&c4,&c5);

  c1=c1+4;
  c2=c2+4;
  c3=c3+4;
  c4=c4+4;
  c5=c5+4;
  
  printf("%c%c%c%c%c%c",c1,c2,c3,c4,c5);
  getchar();

  return 0;

}


















#include <stdio.h>
int main()
 
{

  char c1,c2,c3,c4,c5;

  
  scanf("%c%c%c%c%c",&c1,&c2,&c3,&c4,&c5);

  c1=c1+4;
  c2=c2+4;
  c3=c3+4;
  c4=c4+4;
  c5=c5+4;

  putchar（c1);
 putchar（c1);
 putchar（c1);
 putchar（c1);
 putchar（c1);
 

   getchar();

  return 0;

}


















#include <stdio.h>
#include <math.h>
int main()
 
{



 float r,h,C,S1,S2,V1,V2;
 float Pi=3.14;
	  
  
    
	
	



	printf("请输入半径\nr=");
	scanf( "%f",&r);
	
	printf("\n请输入高\nh=");
	scanf("%f",&h);
	

	 
	C=2*Pi*r;
    S1=Pi*r*r;
    S2=4*Pi*r*r;
	V1=(4.0/3)*Pi*r*r*r;
	V2=S1*h;

	

	printf("\n圆周长C=%.2f\n圆面积S1=%.2f\n圆球表面积S2=%.2f\n圆球体积V1=%.2f\n圆柱体积V2=%.2f",C,S1,S2,V1,V2);


	getchar();

    getchar();
	getchar();
	getchar();


	return 0;
}






















#include <stdio.h>
#include <math.h>
int main()
 
{



 float r,h,C,S1,S2,V1,V2;
 float Pi=3.14;

 
	  
  printf("请输入圆的半径和高\n");
  scanf("%f %f",&r,&h);


    
	

  	 
	C=2*Pi*r;
    S1=Pi*r*r;
    S2=4*Pi*r*r;
	V1=(4.0/3)*Pi*r*r*r;
	V2=S1*h;

	
	printf("圆的周长C=%f",C);





















#include <stdio.h>
#include <math.h>
int main()
 
{



 float r,h,C,S1,S2,V1,V2;
 float Pi=3.14;

 
	  
  printf("请输入圆的半径和高\n");
  scanf("%f %f",&r,&h);


    
	

  	 
	C=2*Pi*r;
    S1=Pi*r*r;
    S2=4*Pi*r*r;
	V1=(4.0/3)*Pi*r*r*r;
	V2=S1*h;

	
	printf("圆的周长C=%.2f\n",C);
	printf("圆的面积S1=%.2f\n",S1);
	printf("圆球的面积S2=%.2f\n",S2);
	printf("圆球的体积V1=%.2f\n",V1);
	printf("圆柱的体积V2=%.2f",V2);


	getchar();
	getchar();
	getchar();
	getchar();
	getchar();




	return 0;



#include <stdio.h>
 int main()

{
	int x;
	printf("请输入成绩:\n");
	scanf("%d",&x);

    if(x<=100&&x>=90)
		printf("成绩等级为:A\n");
	if(x<=89&&x>=80)
		printf("成绩等级为:B\n");
	if(x>=70&&x<=79)
		printf("成绩等级为:C\n");
	if(x>=60&&x<=69)
		printf("成绩等级为:D\n");
	if(x>=0&&x<=59)
		printf("成绩等级为:E\n");
	if(x>100||x<0)
		printf("成绩无效\n");
     

		


























	return 0;

 }




















#include <stdio.h>
 int main()
{
	int x,y;
	printf("请输入成绩\n");
	scanf("%d",&x);
     y=x/10;
	 if(x>=0&&x<=100)
   {switch(y)

	   {
   case 10: printf("成绩等级为:A\n");break;
 
   case 9: printf("成绩等级为:A\n");break;
        case 8: printf("成绩等级为:B\n");break;
	     case 7: printf("成绩等级为:C\n");break;
			   case 6: printf("成绩等级为:D\n");break;
				   default: printf("成绩等级为:E\n");

	 }}
	 else
		 printf("成绩无效");
 







	return 0;

 }




















