Argeset-Stajyer-Meydan-
=======================
Merhaba Argeset Yazılım

#include <stdio.h>
 
#include <stdlib.h>
#include <math.h>
struct cember{
int x,y;
}cember[2];
int main()
{
int i;
float deger=0;
struct cember c[2];
for(i=0;i<2;i++)
{
printf("x koord. gir:"); scanf("%d",&c[i].x);
printf("y koord. gir:"); scanf("%d",&c[i].y);
}
deger=sqrt(pow((c[0].x-c[1].x),2)+pow((c[0].y-c[1].y),2));
printf("deger=%f",deger);
getchar();
getchar();
}
