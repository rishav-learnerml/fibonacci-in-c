# fibonacci in c
 C program to find fibonacci numbers.
 
 code:
 
 #include<stdio.h>
int main()
{
	int n,i=0,c;
	scanf("%d",&n);
	printf("Fibonacci series\n");
	for(c=1;c<=n;c++)
	{
		printf("%d\n",fibonacci(i));
		i++;
	}
	
return 0;
}
int fibonacci(int n)
{
	if(n==0)
	return 0;
	else if(n==1)
	return 1;
	else return(fibonacci(n-1)+fibonacci(n-2));
}

Code executes with 0 error(s)
