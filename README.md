#include <stdio.h>
int operaValores(char operaçao, int valor1, int valor2)
{
  int resultado = 0;

  if (operaçao == 'A')
  {
    resultado = valor1 + valor2;
  }
  else
  {
    resultado = valor1 / valor2;
  }
return resultado;
  }
int main(void) {
int operacao = operaValores('M',6, 2);
printf("O Valor da Operação é:%d", operacao);
return 0;
  }
 
