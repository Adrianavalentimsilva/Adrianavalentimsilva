#include<stdio.h>

int main(void){

 int anos,meses,dias;

printf("Escreva sua idade somente em anos: ");
scanf("%d", &anos);

 printf("\nEscreva sua idade somente em meses: ");
  scanf("%d", &meses);

  printf("\nEscreva sua idade somente em dias: ");
  scanf("%d", &dias);

  dias+=(anos*365)+(meses*30);

 printf("\nSua idade em dias é %d",dias);

 return 0;
}
