#include <stdio.h>
#include <stdlib.h>
int main (){

	float num1,num2,result;
    int opcao;
	//Entrada
	printf("Digite o primeiro numero: \n");
	scanf("%f", &num1);
	printf("Digite o segundo numero: \n");
	scanf("%f", &num2);

	//escolhe a opcao
	printf("Escolha inserindo o nemero referente a operação: \n");
	printf("1 - soma; \n");
    printf("2 - subtracao; \n");
    printf("3 - multiplicacao; \n");
    printf("4 - divisao; \n");
    printf("\n");
    printf("Opcao: \n");
	scanf("%d", &opcao);



	switch (opcao){

        case 1:
            result=num1+num2;
            printf("\nA SOMA do primeiro e segundo numero resulta em: %.2f\n", result);
            break;

        case 2:
            result=num1-num2;
            printf("\nA SUBTRACAO do primeiro e segundo numero resulta em: %.2f\n", result);
            break;

        case 3:
            result=num1*num2;
            printf("\nA MULTIPLICACAO do primeiro e segundo numero resulta em: %.2f\n", result);
            break;

        case 4:
            result=num1/num2;
            printf("\nA DIVISAO do primeiro e segundo numero resulta em: %.2f\n", result);
            break;
	}


return 0;

}
