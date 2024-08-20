# Atividade-4

#include <stdio.h>
#include <stdlib.h>

int main() {
	
    // Declaração da variável para armazenar o número
    int num1, num2;

    // Solicita ao usuário que insira número
    printf ("Digite 2 numeros: \n");
    scanf ("%i", &num1);
    scanf ("%i", &num2);

    // Verifica qual é o Maior de Dois Números:
    if (num1 > num2) {
        printf ("O primeiro numero e maior");
    } else {
        printf ("O segundo numero e maior");
    }

    return 0;
}
