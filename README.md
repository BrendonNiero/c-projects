# Projetos feitos em C
Este repositório contém projetos desenvolvidos em linguagem C. 
Aqui você encontrará instruções para configurar seu ambiente de desenvolvimento e criar seus próprios projetos.


## Instalando o compilador C no Windows
1. Baixe o MinGW em: https://sourceforge.net/projects/mingw/
2. Marque os pacotes mingw32-base e também mingw32-gcc-g++

Observação:
Após a instalação, adicione o caminho do MinGW à variável de ambiente path.
``` bash
C:\MinGW\bin
```


## Está tudo pronto?
Verifique se foi tudo instalado corretamente.

``` bash
gcc --version
```

## Crie um projeto

1. Crie um arquivo chamado main.c
2. Escreva seu código:
``` bash
#include <stdio.h>

int main() {
    printf("Olá, mundo!\n");
    return 0;
}
```
3. No terminal, execute:
``` bash
gcc main.c -o main
```
4. Execute no terminal
``` bash
main
```
