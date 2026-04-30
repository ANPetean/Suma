#include <stdio.h>

int main ()
{
    int sizeA;
    printf("tamanio del areglo\n");
    scanf("%i",&sizeA);
    int age [sizeA];
for (int i =0; i < sizeA;i++ )
{
    printf("ingresa el valor\n",i+1);
    scanf("%i", &age[i]);
}
printf("Los valores del areglo son:\n");
for(int i =0;i < sizeA;i++)
{
    printf("%i-\n", age [i]);
}

    return 0;
}