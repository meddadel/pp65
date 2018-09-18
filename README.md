# pp65
#include<stdio.h>
#include<stdlib.h>
void division (int a,int b,int *r,int *q){
     *q=0;
     if (a==0)
       printf("erreur");
             else if (b>a) *q=0;*r=b;
        while (a>=b){
           a=a-b;
           *q=*q+1;
                   }
     *r=a;
}


main()
{int q,r,a,b;
printf("donner a");
scanf("%d",&a);
printf("donner b");
scanf("%d",&b);
division(a,b,&r,&q);
printf("%d",q);
printf("%d",r);

}
