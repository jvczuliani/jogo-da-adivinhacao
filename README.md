# jogo-da-adivinhacao
Jogo da Adivinhação para a Universidade Anhembi Morumbi
#inclui <stdio.h>
#inclui <stdlib.h>

int main ()
{
    printf("*******************************************\n");
    printf("BEM VINDO AO JOGO DA ADVINHAÇÃO");
    printf("*******************************************\n");

    // 1-> Vai listar para o usuário as dificuldades (1)Fácil (2)Moderado (3)Dificil
    // 2-> LER O VALOR DIGITADO DO USUÁRIO ***********

    // SE FOR FÁCIL GERAMOS UM NÚMERO DE 0-10
    // SE FOR MODERADO GERAMOS UM ALEATÓRIO DE 0-50
    // SE FOR DIFICIL GERAMOS UM DE 0-100

    int numeroAleatorio é= rand () % 50+1 ;
    printf ("%d \n", numeroAleatorio);

    int inputNumber; 

    while (inputNumer != numeroAleatorio)

    {
        // COLETA O INPUT DO USUARIO
        printf("Digite um número: \n");
        scanf("%d", &inputNumber);

        if (inputNumber > numeroAleatorio)
        {
            printf("O número que você digitou, é maior do que o esperado.\n");
        }
        if (inputNumber < numeroAleatorio)
        {
            printf("O número que você digitou, é menor do que o esperado.\n");
        }
        if (inputNumber == numeroAleatorio)
        {
            printf("Você Ganhou!!!!!\n");            
        }

    }

}
