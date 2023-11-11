# Trabal#include <stdio.h>

int main() {
  int i; //declara i

  for (i = 0; i < 100+1; i++) { //para cada valor de i de 0 até 100, com i aumentando de 1 em 1
    if(i % 2 != 0) //se o numero for par mostra na tela, se nao for, nao mostra
        continue; 
    printf("%d\n", i);
      
  }

}ho-
