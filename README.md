//# TO-PRINT-RIGHT-ANGLED-TRINGLE-WITH-01
//DEVELOPED BY VEMULAWADA SWETHA USING C PROGRAMMING LANGUAGE
#include<stdio.h>
int main()
{
    int i,j,n;
    printf("enter the number of rows\n");
    scanf("%d",&n);
    for(i=0;i<=n;i++)
    {
    	
    	for(j=0;j<=i;j++)
    	{
    		printf("01");
		}
		printf("\n");
	}
	return 0;
}
