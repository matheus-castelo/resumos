# Resumão Linguagem C
````c

````
## 1- Tipos Primitivos em C e Declaração de variáveis
````c
// Char, Int, Float, Boolean
tipoPrimitivo nomeDaVariavel = valorDaVariavel; // Declaração
````
## 2- Quantificadores em C
````c
// Short, Long, Signed e Unsigend
````

## 3- Estrutura Básica da linguagem C
````c
#include <stdio.h> // Opcional, mas sem essa biblioteca você não costuma fazer porra nenhuma.
int main () {

    return 0;
}
````

obs: colocar especificadores numero 4 aqui

## 5- Entrada e Saída de dados em C
````c
// ENTRADA DE DADOS
scanf("%n",&nomeDaVariavel); // Sendo n um especificador

// SÁIDA DE DADOS
printf("Sua variável é: %n", nomeDaVariavel); // Sendo n um especificador
//ou use puts(""); mas não terá formatação
````

## 6- Incremento e Decremento | Pré e Pós
````c
// Incremento ++ e Decremento --
// Pré = Executa o incrementa e depois faz a ação
// Pós = Executa a ação e depois faz o incremento
````



## 7- Operadores de Comparação
````c
// São eles =, !=, >, <, >= e <=
````
OBS: Em estruturas condicionais, 0 é falso e qualquer coisa diferente de 0 é verdadeiro !

## 8- Estrutura de Repetição For, While e Do-While
````c
// For (os parâmetros correspondem a Start, Stop e Step)
for (int i=0 ; i < 100 ; i++){
    //bloco de código a ser executado
}

// While
while (condicao){
    //bloco de código a ser executado
}

do {
    // bloco de código a ser executado
}
while (condicao)
````

## 9- Estruturas Condicionais If, Else e Else-If
````c
if (condicao){
    //bloco de código a ser executado
}
else if (condicao){
    // bloco de código a ser executado
}
else {
    //bloco de código a ser executado
}
````

## 10- Continue e Break
````c
// Continue = Achou o continue ? Volta para o início do laço
// Break = Interrompe o laço mais interno e vai para próxima interação 
````