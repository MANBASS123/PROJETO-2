#include <stdio.h>

int main(void)
{

    
    // declaraçao de variaveis
    int nota1, nota2, nota3, media;
    
    // entrada de dados //
    
    printf("digite a primeira nota do aluno: ");
    scanf("%i", &nota1);
    
     printf("digite a segunda nota do aluno: ");
    scanf("%i", &nota2);
    
    printf("digite a terceira nota do aluno: ");
      scanf("%i", &nota3);
   
   
    //processamento
    media= (nota1 + nota2 + nota3) / 3;
    
    //saida//
    printf("media do aluno = %i\n", media) ;
if (media >=8) {
    printf("aprovado"); }

      
    else printf("reprovado");
    
}
