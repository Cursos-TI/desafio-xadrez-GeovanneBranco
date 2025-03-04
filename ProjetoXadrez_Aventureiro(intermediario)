#include <stdio.h>
#include <string.h>

int main()
{

    // declaracao de variaveis que o programa vai rodar.
    //
    int casas, direcao, direcao2, peca, torre, bispo, rainha, i, j;
    char movimento[50], movimentos[50], movimentos2[50];

    // aqui implementei uma entrada de dados para que o usuario escolha qual das pecas ele deseja mover atraves de um switch.
    //
    printf(" Qual pecas de xadrez voce deseja mover:\n");
    printf(" 1. Torre\n");
    printf(" 2. Bispo\n");
    printf(" 3. Rainha\n");
    printf(" 4. Cavalo\n");
    scanf("%d", &peca);

    // inicio do nosso switch onde dentro dele tem uma estrutura de if-else e tambem uma estrutura de for.
    //
    switch (peca)
    {

    case 1:
        // Aqui o usuario vai escolher para qual direcao a peca Torre vai se mover.
        //
        printf("Qual direcao:\n");
        printf(" 1. cima\n");
        printf(" 2. baixo\n");
        printf(" 3. direita\n");
        printf(" 4. esquerda\n");
        scanf("%d", &direcao);

        // de acordo com a entrada da variavel direcao nosso if-else vai agregar o valor da string movimentos para que o texto seja correspondente.
        //
        if (direcao == 1)
        {
            char movimento[] = "para cima";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 2)
        {
            char movimento[] = "para baixo";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 3)
        {
            char movimento[] = "para a direita";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 4)
        {
            char movimento[] = "para a esquerda";
            strcpy(movimentos, movimento);
        }
        else
        {
            printf(" Movimento invalido");
        }

        // Aqui vamos agregar valor a variavel inteira casas que determina quantas vezes nossa peca vai se mover
        // a variavel casas tambem sera o numero de repeticoes fixas da nossa estrura for.
        //
        printf("quantas casas: ");
        scanf("%d", &casas);
        printf(" A torre se move...\n");

        // nossa estrura for vai exibir o a direcao de movimento escolhida pelo usuaria anteriomente pela quantidade de vezes da variavel casas.
        //
        for (i = 0; i < casas; i++)
        {
            printf("%s\n", movimentos);
        }
        break;
    case 2:
        //
        //
        printf("Qual direcao:\n");
        printf(" 1. Diagonal: Cima Esquerda\n");
        printf(" 2. Diagonal: Cima Direita\n");
        printf(" 2. Diagonal: Baixo Direita\n");
        printf(" 4. Diagonal: Baixo Esquerda\n");
        scanf("%d", &direcao);

        // de acordo com a entrada da variavel direcao nosso if-else vai agregar o valor da string movimentos para que o texto seja correspondente.
        //
        if (direcao == 1)
        {
            char movimento[] = "para a diagonal Cima Esquerda";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 2)
        {
            char movimento[] = "para a diagonal Cima Direita";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 3)
        {
            char movimento[] = "para a diagonal Baixo Direita";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 4)
        {
            char movimento[] = "para a diagonal Baixo Esquerda";
            strcpy(movimentos, movimento);
        }
        else
        {
            printf(" Movimento invalido");
        }

        // Aqui vamos agregar valor a variavel inteira casas que determina quantas vezes nossa peca vai se mover
        // a variavel casas tambem sera o numero de repeticoes fixas da nossa estrura for.
        //
        printf("quantas casas: ");
        scanf("%d", &casas);
        printf(" O bispo se move...\n");

        // nossa estrura for vai exibir o a direcao de movimento escolhida pelo usuaria anteriomente pela quantidade de vezes da variavel casas.
        //
        for (i = 0; i < casas; i++)
        {
            printf("%s\n", movimentos);
        }
        break;
    case 3:

        printf("Qual direcao:\n");
        printf(" 1. cima\n");
        printf(" 2. baixo\n");
        printf(" 3. direita\n");
        printf(" 4. esquerda\n");
        printf(" 5. Diagonal: Cima Esquerda\n");
        printf(" 6. Diagonal: Cima Direita\n");
        printf(" 7. Diagonal: Baixo Direita\n");
        printf(" 8. Diagonal: Baixo Esquerda\n");
        scanf("%d", &direcao);

        // de acordo com a entrada da variavel direcao nosso if-else vai agregar o valor da string movimentos para que o texto seja correspondente.
        //
        if (direcao == 1)
        {
            char movimento[] = "para cima";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 2)
        {
            char movimento[] = "para baixo";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 3)
        {
            char movimento[] = "para a direita";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 4)
        {
            char movimento[] = "para a esquerda";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 5)
        {
            char movimento[] = "para a diagonal Cima Esquerda";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 6)
        {
            char movimento[] = "para a diagonal Cima Direita";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 7)
        {
            char movimento[] = "para a diagonal Baixo Direita";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 8)
        {
            char movimento[] = "para a diagonal Baixo Esquerda";
            strcpy(movimentos, movimento);
        }
        else
        {
            printf(" Movimento invalido");
        }

        // Aqui vamos agregar valor a variavel inteira casas que determina quantas vezes nossa peca vai se mover
        // a variavel casas tambem sera o numero de repeticoes fixas da nossa estrura for.
        //
        printf("quantas casas: ");
        scanf("%d", &casas);
        printf(" A Rainha se move...\n");

        // nossa estrura for vai exibir o a direcao de movimento escolhida pelo usuaria anteriomente pela quantidade de vezes da variavel casas.
        //
        for (i = 0; i < casas; i++)
        {
            printf("%s\n", movimentos);
        }
        break;

    case 4:

        printf(" o cavalo se movimenta faz um movimento em 'L' em 3 casas, 2 em linha reta e 1 para os lados.");
        printf("Qual direcao ele vai andar em linha reta:\n");
        printf(" 1. cima\n");
        printf(" 2. baixo\n");
        printf(" 3. direita\n");
        printf(" 4. esquerda\n");
        scanf("%d", &direcao);

        if (direcao == 1 || direcao == 2)
        {
            printf("Qual direcao ele vai andar  para o lado:\n");
            printf(" 1. direita\n");
            printf(" 2. esquerda\n");
            scanf("%d", &direcao2);
            if (direcao2 < 1 || direcao2 > 2)
            {
                printf("opcao invalida\n");
                return 0;
            }
        }
        else if(direcao == 3 || direcao == 4){

            printf("Qual direcao ele vai andar em  para o lado2:\n");
            printf(" 1. cima\n");
            printf(" 2. baixo\n");
            scanf("%d", &direcao2);
            if (direcao2 < 1 || direcao2 > 2)
            {
                printf("opcao invalida\n");
                return 0;
        }
        }

        // de acordo com a entrada da variavel direcao nosso if-else vai agregar o valor da string movimentos para que o texto seja correspondente.
        //
        if (direcao == 1)
        {
            char movimento[] = "para cima";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 2)
        {
            char movimento[] = "para baixo";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 3)
        {
            char movimento[] = "para a direita";
            strcpy(movimentos, movimento);
        }
        else if (direcao == 4)
        {
            char movimento[] = "para a esquerda";
            strcpy(movimentos, movimento);
        }
        else
        {
            printf(" Movimento invalido");
        }

        if (direcao2 == 1)
        {
            char movimento[] = "para cima";
            strcpy(movimentos2, movimento);
        }
        else if (direcao2 == 2)
        {
            char movimento[] = "para baixo";
            strcpy(movimentos2, movimento);
        }
        else if (direcao2 == 3)
        {
            char movimento[] = "para a direita";
            strcpy(movimentos2, movimento);
        }
        else if (direcao2 == 4)
        {
            char movimento[] = "para a esquerda";
            strcpy(movimentos2, movimento);
        }
        else
        {
            printf(" Movimento invalido");
        }

        // nossa estrura for vai exibir o a direcao de movimento escolhida pelo usuaria anteriomente pela quantidade de vezes da variavel casas.
        //
        for (i = 0; i < 1; i++)
        {
            for (j = 0; j < 2; j++)
            {
                printf("%s\n", movimentos);
            }
            printf("%s\n", movimentos2);
            printf("\n");
        }
        break;
    }

    return 0;
}
