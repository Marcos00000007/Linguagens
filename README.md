# Linguagens
projetos de linguagem c, c++, c#, java, python, etc...
/******************************************************************************
 * Tabuada: liguagem C
*******************************************************************************/
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
/******************************************************************************
 * soma e media em vetores liguagem C
*******************************************************************************/
#include <stdio.h>

int main()
{
    
    int n, i, soma, qtd;
    double media;
    printf("Digite quantos numeros voce vai digitar: ");
    scanf("%d", &n);
    int vet[n];
    soma = 0;
    qtd = 0;
    for(i = 0; i < n;i++){
        printf("Digite um numero: ");
        scanf("%d", &vet[i]);
        soma = soma + vet[i];
        qtd = qtd + 1;
    }
    media = (double)soma / qtd;
    printf("\nVALORES: \n");
    for(i = 0; i < n;i++){
        printf("%.1d  ", vet[i]);
        }
    printf("\nSOMA= %.2d\n", soma);
    printf("MEDIA= %.2lf", media);
    return 0;
}
