# fmu-calculo-de-aumento-salarial
 📚 APS – Lógica de Programação 1º semestre
 \
 👨🏻‍🏫 Profº Silvio 
 \
 👩🏻‍🏫 Profª Talita
 \
 \
 **DEV/ALUNO:**
- 👨🏻‍🎓 Marcus Satirio da Mata Neves - 6932681
 \
 \
 Questão 3
 
 - Faça  um  programa  que  receba  o  código  correspondente  ao  cargo  de  um  funcionário  e  seusalário atual e mostre o cargo, o valor do aumento e seu novo salário. Os cargos estão na tabela a seguir:
 [tabela](https://i.imgur.com/fTUWkYy.png "tabela")
\
\
\
**CÓDIGO**
~~~C
#include <stdio.h>
#include <stdlib.h>

int main()
{
int opcao;
double salarionovo;
double salariobase;
double dif;
double aumento;

    printf("FACULDADE METROPOLITANAS UNIDAS");
    printf(" \n");
    printf(" \n");
    printf("APS - LOGICA DE PROGRAMACAO - 1º SEMESTRE");
    printf(" \n");
    printf(" \n");
    printf("Desenvolvedor: Marcus Neves\n");
    printf("RA: 6932681\n");
    printf("Contato: marcus-neves@outlook.com\n");
    printf(" \n");
    printf("******************\n");
    printf("*fmu-calculo-de-aumento-salarial*\n");
    printf("******************\n");
    printf("\nCódigo |    Cargo     | Percentual");
    printf("\n 1     | Escriturário |     50%%  ");
    printf("\n 2     | Secretária   |     35%%  ");
    printf("\n 3     |    Caixa     |     20%%  ");
    printf("\n 4     |   Gerente    |     10%%  ");
    printf("\n 5     |   Diretor    |     0%%   ");
    printf("\nDigite o código do cargo correspondente:");
    scanf("%d", &opcao);
      if(opcao == 1){
          printf("\nCARGO SELECIONADO: Escriturário");
          printf("\nDIGITE O SALÁRIO BASE:");
          scanf("%lf",&salariobase);
          printf("\nO CARGO ESCRITURÁRIO ESTÁ ELEGÍVEL Á 50%% DE AUMENTO");
          printf("\nSALÁRIO ANTIGO: %f", salariobase);
          aumento = salariobase * 0.5;
          salarionovo = salariobase + aumento;
          printf("\nVALOR DO AUMENTO: %f", aumento);
          printf("\nSALÁRIO AJUSTADO: %f\n", salarionovo);
      }
      if(opcao == 2){
          printf("\nCARGO SELECIONADO: Secretária");
          printf("\nDIGITE O SALÁRIO BASE:");
          scanf("%lf",&salariobase);
          printf("\nO CARGO SECRETÁRIA ESTÁ ELEGÍVEL Á 35%% DE AUMENTO");
          printf("\nSALÁRIO ANTIGO: %f", salariobase);
          aumento = salariobase * 0.35;
          salarionovo = salariobase + aumento;
          printf("\nVALOR DO AUMENTO: %f", aumento);
          printf("\nSALÁRIO AJUSTADO: %f\n", salarionovo);
      }
      if(opcao == 3){
          printf("\nCARGO SELECIONADO: Caixa");
          printf("\nDIGITE O SALÁRIO BASE:");
          scanf("%lf",&salariobase);
          printf("\nO CARGO CAIXA ESTÁ ELEGÍVEL Á 20%% DE AUMENTO");
          printf("\nSALÁRIO ANTIGO: %f", salariobase);
          aumento = salariobase * 0.20;
          salarionovo = salariobase + aumento;
          printf("\nVALOR DO AUMENTO: %f", aumento);
          printf("\nSALÁRIO AJUSTADO: %f\n", salarionovo);
      }
      if(opcao == 4){
          printf("\nCARGO SELECIONADO: Gerente");
          printf("\nDIGITE O SALÁRIO BASE:");
          scanf("%lf",&salariobase);
          printf("\nO CARGO GERENTE ESTÁ ELEGÍVEL Á 10%% DE AUMENTO");
          printf("\nSALÁRIO ANTIGO: %f", salariobase);
          aumento = salariobase * 0.10;
          salarionovo = salariobase + aumento;
          printf("\nVALOR DO AUMENTO: %f", aumento);
          printf("\nSALÁRIO AJUSTADO: %f\n", salarionovo);
      }
      if(opcao == 5){
          printf("\nCARGO SELECIONADO: Diretor");
          printf("\nDIGITE O SALÁRIO BASE:");
          scanf("%lf",&salariobase);
          printf("\nO CARGO DIRETOR NÃO ESTÁ ELEGÍVEL Á NENHUM TIPO DE AUMENTO");
          printf("\nSALÁRIO ATUAL: %f\n", salariobase);
      }
      else
      {
          printf("\nOPÇÃO INVÁLIDA, TENTE NOVAMENTE!\n");
      }
}
~~~
