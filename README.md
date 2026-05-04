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
# 1. Inicia el repositorio local
git init

# 2. Crea un archivo README para explicar tu proyecto
# (Esto es excelente para tu portafolio)
echo "# Fundamentos de Programación en C" >> README.md

# 3. Agrega todos tus archivos (.c y el README)
git add .

# 4. Crea tu primer "commit" (registro de cambios)
git commit -m "Primeros pasos: Lógica, variables y operador ternario"

# 5. Conecta tu PC con el repositorio que creaste en la web
# Reemplaza 'TU_USUARIO' con tu nombre de usuario real
git remote add origin https://github.com/TU_USUARIO/fundamentos-programacao-c.git

# 6. Sube los archivos
git push -u origin main
