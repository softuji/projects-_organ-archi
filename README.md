### Projects in development for Archicteture and Organization class
## Class 1
Tema: A Lógica da Comparação e da Soma

Este programa baseado nos códigos do doecente foi transformado em Python, onde realiza a soma lógica de dois números inteiros a e b utilizando apenas 
operações bitwise (^,& e |). 
* Ele converte os números inteiros para representação binária, realiza a soma bit a bit, levando em conta o vai-um (carreador), e então converte o resultado de volta para decimal.
* A função principal soma_logica(a, b) realiza a soma lógica entre a e b, onde va e vb são as representações binárias de a e b.
* As funções binario(dec) e decimal(vet) são utilizadas para converter entre números decimais e binários.

O programa permite a opção do usuário inserir os valores de a e b, e em seguida, compara a soma usando operadores tradicionais e operadores lógicos.

## Class 2
Tema: Programa para Conversão de Decimal para Hexadecimal

Na busca de compreender o código de blocos, foi realizado sua adaptação em C que faz solicitação ao usuário por um número decimal inteiro, e em seguida realiza a conversão desse número para sua representação hexadecimal.
* O processo é iniciado dividindo repetidamente o número decimal por 16 e armazenando os restos da divisão como dígitos hexadecimais. 
* A função inv_str é utilizada para inverter a sequência de dígitos hexadecimais obtidos, o que confere a representação final seja correta. Durante a conversão, os dígitos hexadecimais são armazenados em um array de strings chamado vHexas. 
* O loop continua até que o valor decimal seja menor ou igual a 16.

Após a conversão, o programa exibe o valor hexadecimal resultante precedido por "0x" através de um alerta na janela do navegador. 

## Class 3
Tema: Programa para simular a Execução de Comandos Simples

O programa tenta simular o funcionamento de uma CPU com operações matemáticas simples e sua entrada.
* Foram utilizadas variáveis simples para representar as operações.
* A função cpu recebe um código de operação, dois operandos e executa a operação correspondente (no lugar do nome, número funciona) dentro das estruturas de condições if, retornando o resultado.
* Assim como na versão em C++ fornecida, a divisão por zero retorna -1 para indicar um erro, e se a operação não for reconhecida, retorna -2.

No print, chama-se a função cpu com diferentes operações e operandos, imprimindo os resultados diretamente.

## Class 4
Tema: Tentativa de entender 'classe' em C

Em C, não há suporte nativo para classes como em linguagens de programação orientadas a objetos.

No entanto, o programa utiliza uma estrutura para encapsular um ponteiro de função, que é um recurso que pode ser usado para simular o comportamento de métodos em classes. 
* A estrutura typedef struct em C é uma construção usada para criar um novo tipo de dado definido pelo usuário, que combina uma estrutura (struct) com um apelido que pode ser usado para se referir a 
essa estrutura usando um nome mais curto e legível. Então, a estrutura foi chamada ULA que contém um único membro, o ponteiro para função chamado exec.
* Foi utilizada a estrutura ULA para representar a Unidade Lógica e Aritmética.
* Dentro da estrutura, define um ponteiro para função exec que recebe três argumentos (a operação, e os operandos).
* Foram definidas funções separadas (add, sub, mul, division) para cada operação, e o ponteiro exec é atribuído a cada uma delas conforme a operação desejada.
* As funções retornam o resultado da operação ou, no caso da divisão por zero, exibem uma mensagem de erro e retornam um valor indicando erro (-1).

No main(), foi atribuído o ponteiro exec à função correspondente a cada operação e exibiu o resultado da operação realizada.
