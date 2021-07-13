#include<stdio.h>
#include<string.h>
struct book
{
    int pages;
    float price;
    char name[20];
}b;
int main()
{
    b.pages=880;
    b.price=990.65;
    strcpy(b.name,"My name is Divya");
    printf("\n %d ",b.pages);
    printf("\n %f ",b.price);
    printf("\n %s",b.name);
    return 0;
}
