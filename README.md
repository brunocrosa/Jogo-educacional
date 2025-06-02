#include <stdio.h>

int main() {
    int resposta, pontos = 0;

    printf("=== QUIZ DE PROGRAMACAO EM C ===\n\n");

    printf("1) Qual comando usamos para imprimir algo na tela?\n");
    printf("1 - scanf\n2 - printf\n3 - main\n");
    printf("Sua resposta: ");
    scanf("%d", &resposta);
    if (resposta == 2) {
        printf("Correto!\n\n");
        pontos++;
    } else {
        printf("Errado. A resposta correta era 2 - printf\n\n");
    }

    printf("2) Qual tipo usamos para declarar um numero inteiro?\n");
    printf("1 - float\n2 - char\n3 - int\n");
    printf("Sua resposta: ");
    scanf("%d", &resposta);
    if (resposta == 3) {
        printf("Correto!\n\n");
        pontos++;
    } else {
        printf("Errado. A resposta correta era 3 - int\n\n");
    }

    printf("3) Qual simbolo usamos para comparar igualdade em C?\n");
    printf("1 - =\n2 - ==\n3 - !=\n");
    printf("Sua resposta: ");
    scanf("%d", &resposta);
    if (resposta == 2) {
        printf("Correto!\n\n");
        pontos++;
    } else {
        printf("Errado. A resposta correta era 2 - ==\n\n");
    }

    printf("4) Qual funcao marca o inicio de um programa em C?\n");
    printf("1 - void\n2 - int\n3 - main\n");
    printf("Sua resposta: ");
    scanf("%d", &resposta);
    if (resposta == 3) {
        printf("Correto!\n\n");
        pontos++;
    } else {
        printf("Errado. A resposta correta era 3 - main\n\n");
    }

    printf("5) O que significa '%%d' em printf?\n");
    printf("1 - caractere\n2 - inteiro\n3 - decimal\n");
    printf("Sua resposta: ");
    scanf("%d", &resposta);
    if (resposta == 2) {
        printf("Correto!\n\n");
        pontos++;
    } else {
        printf("Errado. A resposta correta era 2 - inteiro\n\n");
    }

    printf("=== Fim do Jogo ===\n");
    printf("Voce acertou %d de 5 perguntas.\n", pontos);

    return 0;
}
