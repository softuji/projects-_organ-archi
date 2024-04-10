### Projects in development for Archicteture and Organization class
# Avaliação 1
### Class 1
Tema: A Lógica da Comparação e da Soma

Este programa baseado nos códigos do doecente foi transformado em Python, onde realiza a soma lógica de dois números inteiros a e b utilizando apenas 
operações bitwise (^,& e |). 
* Ele converte os números inteiros para representação binária, realiza a soma bit a bit, levando em conta o vai-um (carreador), e então converte o resultado de volta para decimal.
* A função principal soma_logica(a, b) realiza a soma lógica entre a e b, onde va e vb são as representações binárias de a e b.
* As funções binario(dec) e decimal(vet) são utilizadas para converter entre números decimais e binários.

O programa permite a opção do usuário inserir os valores de a e b, e em seguida, compara a soma usando operadores tradicionais e operadores lógicos.

### Class 2
Tema: Programa para Conversão de Decimal para Hexadecimal

Na busca de compreender o código de blocos, foi realizado sua adaptação em C que faz solicitação ao usuário por um número decimal inteiro, e em seguida realiza a conversão desse número para sua representação hexadecimal.
* O processo é iniciado dividindo repetidamente o número decimal por 16 e armazenando os restos da divisão como dígitos hexadecimais. 
* A função inv_str é utilizada para inverter a sequência de dígitos hexadecimais obtidos, o que confere a representação final seja correta. Durante a conversão, os dígitos hexadecimais são armazenados em um array de strings chamado vHexas. 
* O loop continua até que o valor decimal seja menor ou igual a 16.

Após a conversão, o programa exibe o valor hexadecimal resultante precedido por "0x" através de um alerta na janela do navegador. 

### Class 3
Tema: Programa para simular a Execução de Comandos Simples

O programa tenta simular o funcionamento de uma CPU com operações matemáticas simples e sua entrada.
* Foram utilizadas variáveis simples para representar as operações.
* A função cpu recebe um código de operação, dois operandos e executa a operação correspondente (no lugar do nome, número funciona) dentro das estruturas de condições if, retornando o resultado.
* Assim como na versão em C++ fornecida, a divisão por zero retorna -1 para indicar um erro, e se a operação não for reconhecida, retorna -2.

No print, chama-se a função cpu com diferentes operações e operandos, imprimindo os resultados diretamente.

### Class 4
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

# Avaliação 2
### Class 6
Tema: Clonar o 00-99 Digital Counter e inserir um terceiro display, permitindo contagens até 999 no Tinkercad.

* O desafio de ajustar o terceiro display foi relativamente fácil de compreender, levando em consideração a devida atenção na resistência. Na parte do código, houve necessidade de ajustar no loop for, inserção da nova entrada digital e recalcular as casas decimais em cada display.
  
Link para o projeto: https://www.tinkercad.com/things/14oGTTnOmYy-experiment-000-999-digital-counter?sharecode=xy-UlgUi9mDg295t8kQMfWR9BGGYZEdZr8L6iNt0r8U

### Class 7
Tema: Na linguagem de programação C, foi implementada em POO uma simulação de Acesso a Dados em RAM para configuração de 2x1024x16.

* A estrutura do programa reflete a organização típica de uma memória RAM em um sistema computacional, onde os dados são acessados por meio de endereços de memória.
* A função Memoria inicializa toda a memória RAM com zeros, imitando o comportamento comum de inicialização da memória em sistemas computacionais.
* A função acesso simula operações de leitura e escrita na memória RAM, onde os dados são acessados por meio de um endereço de memória (mar) e o dado a ser lido/escrito (mbr), com base no modo de operação especificado (READ/WRITE).

Link para o projeto: https://www.jdoodle.com/ia/ZXU

### Class 8
Tema: Fazer programa (funções para geração e teste) para implementar paridade par.

O código fez uso das seguintes funções: 
* A função calcular_paridade_par gera a paridade par para uma lista de bits dada.
* A função verificar_paridade testa se a paridade par de uma lista de bits é 0 (o que significa que é par) ou não.
* O exemplo de uso demonstra como chamar a função verificar_paridade com uma lista de bits para verificar se a paridade é par ou não.

Paridade Par em Sistemas de Comunicação e Armazenamento de Dados:

O programa implementa o conceito de paridade par, que é uma técnica comumente usada em sistemas de comunicação e armazenamento de dados para detecção de erros. A paridade par é uma forma simples de verificação de erro, onde um bit adicional (bit de paridade) é adicionado a um conjunto de bits para garantir que o número total de bits 1 seja sempre par.

Programação Funcional em Python: A utilização de iterações com for e a operação XOR (^) em Python torna o código mais conciso e legível.

### Class 9
Tema: Na Simulação de ULA, Implementar geração de Flags para: Zero, Negativo e Overflow.


Link para o projeto: https://www.jdoodle.com/ia/ZYg
