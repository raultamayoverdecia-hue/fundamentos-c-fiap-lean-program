# fundamentos-c-fiap-lean-program
En el cuadro de texto escribe un mensaje corto, por ejemplo: Subiendo primer ejercicio de C.em curso de Lear program
programa
{
    funcao inicio()
    {
        inteiro nota1, nota2
        real media

        media = (nota1 + nota2) / 2

        escreva(media)
    }
}
#include <stdio.h>

char msg[9] = "Ola Mundo";

#define PI 3.14

int main()
{
    double i = 0;
    printf(msg);
    i = 1 * PI;
    printf("\n\r%d", i); // Nota: El %d aquí daría un error de tipo con double, se usa solo para demostración.
    return 0;
}
#include <stdio.h>

int main()
{
    float nota_final, nota1, nota2;

    printf("Entre o valor da nota 1: ");
    scanf("%f", &nota1);

    printf("Entre o valor da nota 2: ");
    scanf("%f", &nota2);

    // Uso del operador ternario para encontrar la nota mayor
    nota_final = (nota1 > nota2) ? nota1 : nota2;

    return 0;
}
