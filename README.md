# repo-para-fork
Código simples baseado em programa C ou C++ para identificar o nome da pessoa que estiver digitando no terminal.
-
#include <stdio.h>
#include <locale.h>

int main(){
    setlocale(LC_ALL, "Portuguese");
    char txt1[20];
    char txt2[20];
    printf("Digite seu nome:\n");
    scanf("%s", &txt1);
    printf("Digite um sobrenome:\n");
    scanf("%s", &txt2);
    printf("%s %s", &txt1, &txt2);
    
    return 0;
}
-
Obrigado pela ajuda!!!
