#define_CRT_SECURE_NO_WARNINGS
#include<stdio.h>
#include<stdlib.h>
int main()
{ 
int i,n,căutat,a[100],ok=0; 
printf(“ dați numărul de elemente: “);
for(i=0;i<n;i++)
{ 
printf(“\n introduceți elementul %d”,i+1);
scanf(“%d”, &a[i]);
}
printf(“\n introduceți elementul căutat: “);
for(i=0;i<n;i++)
if(a[i]==căutat)
{
printf(“\n elementul căutat se afla pe poziția %d”,i+1);
ok=1;
break;
}
if(ok==0)
printf(“\n elementul căutat nu se afla in șir”);
system(“pause”);
return 0;
}


