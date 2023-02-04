//# profit_loss.c//
#include<stdio.h>
int main()
{
    float pv,sv,p,l;
    printf("Enter the purchase value:");
    scanf("%f",&pv);
    printf("Enter the selling value:");
    scanf("%f",&sv);
    if(pv>sv)
    {
        l=pv-sv;
        printf("loss=%f\n",l);
        printf("you made a loss.");
    }
    else
    {
        p=sv-pv;
        printf("profit=%f\n",p);
        printf("you made a profit.");
    }
}
