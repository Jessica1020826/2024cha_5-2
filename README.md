# 2024cha_5-2
#include <stdio.h>

int min(int a,int b){
    int v_min = 0;
    if (a > b){
    v_min = b;
    
   }else{
    v_min = a;
   }
   return v_min;
}
   int max(int a,int b){
    int v_max = 0;
    
    return v_max;
   }
    int main()
{
    int a,b;
    printf("please input a =");
	scanf("%d",&a);
	printf("please input b =");
	scanf("%d",&b);
	printf("min value = %d",min(a,b));
	

    return 0;
}
