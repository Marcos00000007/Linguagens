# Linguagens
projetos de linguagem c, c++, c#, java, python, etc...

#include <stdio.h>

int main()
{   
    
    int n, i , produto;
    printf("Deseja a tabuada de qual valor? ");
    scanf("%d", &n);
    for (i=1;i <= 10;i++){
        produto = n * i;
        printf("%d x %d = %d\n",n ,i ,produto);
    }
    
    return 0;
}
