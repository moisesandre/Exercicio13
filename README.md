# Exercicio13

#include <stdio.h>
#include <stdlib.h>

int main()

{
    system("color 0b");
    int i, n[20], q, soma=0;

    for (i=0; i<=19; i++)
    {
        printf("Digite um numero: ");
        scanf("%d", &n[i]);
    }

    for (i=0; i<=19; i++)
    {
        q=n[i]*n[i];

        if (q<225)
        {
            soma= soma+q;
        }
    }

    printf("Resultado da soma dos quadrados dos nmrs digitados: %d\n", soma);
    printf("OBS: os quadrados que passam de 225 nao sao contabilizados\n");

return 0;
}
