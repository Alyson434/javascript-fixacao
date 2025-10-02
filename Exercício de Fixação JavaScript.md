**Exercício de Fixação JavaScript – Word e GitHub** 

 

 

**Nome: \_\_\_\_\_\_\_\_Alyson veríssimo\_\_\_\_\_\_\_\_\_\_\_\_\_\_** 

**Data: \_\_\_\_\_\_\_\_\_\_\_01/10/2025\_\_\_\_\_\_\_\_\_\_\_** 



**2.1 Variáveis e Tipos** 

**● Qual a diferença entre var, let e const?**

**var-> tem escopo de função ou global e pode ser reatribuído e redeclarado.** 

**let-> tem escopo de bloco e pode ser reatribuído, mas não redeclarado.** 

**const-> também tem escopo de bloco, mas, além de não poder ser redeclarado, também não pode ser reatribuído após a inicialização.**  



**● Liste os tipos primitivos do JavaScript com exemplos.** 

**->String, Number, BigInt, Boolean, Undefined, Symbol e Null.**



**● Qual a diferença entre null e undefined?** 

**-> null é um valor atribuído intencionalmente para indicar a ausência de um valor, enquanto undefined indica que uma variável foi declarada mas ainda não recebeu um valor.**

**● Explique == e ===.** 

**null -> É um valor que o desenvolvedor, atribui a uma variável de forma intencional.** 

**undefined -> Ocorre automaticamente quando uma variável é declarada, mas nunca recebe um valor.**



**2.2 Operadores e Expressões** 

**● Liste operadores matemáticos: +, -, \*, /.**

**Sinal de + realiza a operação de adição ,somando dois ou mais números.**

**Sinal de - realiza a operação de subtração, subtraindo um número do outro, ou pode ser usado para indicar um número negativo.**

**Sinal de \* realiza a operação de multiplicação.** 

**Sinal de / realiza a operação de divisão, dividindo o número da esquerda pelo número da direita.** 



**● Liste operadores lógicos: \&\&, ||, !.** 

**\&\& -> Este operador lógico binário retorna verdadeiro (TRUE) apenas se ambas as condições forem verdadeiras.**

**|| -> Este operador lógico binário retorna verdadeiro (TRUE) se pelo menos uma das condições for verdadeira.**

**!  -> Este operador unário inverte o valor booleano de uma expressão. Se uma condição é verdadeira, o ! a torna falsa, e vice-versa.** 



**● Preveja os resultados:** 

**○ "5" + 2** 

**O resultado da operação "5" + 2 é a concatenação das strings "5" e 2, resultando em "52", pois o + entre uma string e um número realiza uma concatenação e não uma soma aritmética.** 

**○ true + 1** 

**Dica: Escreva mentalmente como se fosse código, ex.:** 

**let soma = "5" + 2; // Saída prevista: "52"** 

**2.3 Estruturas de Controle** 

**● Explique if, else if e else.** 

**if -> Executa um bloco de código apenas se uma condição especificada for verdadeira.**

**else if -> Se a condição do if for falsa, verifica uma nova condição. Se essa nova condição for verdadeira, o código associado a ela é executado.**

**else ->  Se nenhuma das condições anteriores (if ou else if) for verdadeira, um bloco de código alternativo é executado.**



**● Como usar switch?** 

**Quando for verificar se um valor corresponde a algum de um conjunto pré-determinado de valores.**

**● Escreva um exemplo de verificação de maioridade.** 



**function verificarMaioridade(idade) {**

    **if (idade >= 18) {**

        **return "Maior de idade";**

    **} else {**

        **return "Menor de idade";**

    **}**

**}**



**let idade = parseInt(prompt("Digite sua idade:"));**

**let resultado = verificarMaioridade(idade);**

**console.log(resultado);**



**2.4 Loops e Repetições** 

**● Liste os tipos de loops: for, while, do...while.** 

**for -> Executar um bloco de código um número específico de vezes.** 

**while ->  Executar um bloco de código enquanto uma determinada condição for verdadeira.** 

**do...while -> Executar um bloco de código pelo menos uma vez, e continuar repetindo enquanto uma condição for verdadeira.** 



**● Escreva mentalmente como imprimir números de 1 a 5.** 

**● Explique break e quando usá-lo.** 

**-> É usada para interromper imediatamente a execução de um loop for, while, do-while ou de uma estrutura switch-case, permitindo que o programa continue na próxima instrução após o bloco. Ela é útil para sair de um loop assim que uma condição específica é atendida, como encontrar um item desejado em uma lista, ou para evitar a execução de código desnecessário em situações de erro.** 



**2.5 Funções** 

**● O que é uma função?** 

**É uma relação matemática entre dois conjuntos, onde cada elemento do primeiro conjunto (o domínio) está associado a um único elemento do segundo conjunto**



**● Diferença entre função declarada e função expressa.** 

**Declarada-> É quando você declara a função de forma tradicional,usando a palavra-chave function no início.**

**Expressa-> É quando você cria uma função e atribui ela a uma variável ou constante.**



**● Crie uma função que recebe um nome e retorna saudação.** 



**const saudacao = function(nome) {**

  **return Olá, ${nome}! Seja bem-vindo.;**

**};**

**console.log(saudacao("Alyson"));** 

**// Saída: Olá, Alyson! Seja bem-vindo.**



**2.6 Mini-casos práticos** 

**● Verificação de número par ou ímpar.**



**const verificarParOuImpar = function(numero) {**

  **return numero % 2 === 0 ? ${numero} é par. : ${numero} é ímpar.;**

**};**

**console.log(verificarParOuImpar(4)); // 4 é par.**

**console.log(verificarParOuImpar(9)); // 9 é ímpar.** 



**● Criação mental de uma lista de compras (array).** 



**let listaDeCompras = \["Arroz", "Feijão", "Leite", "Pão"];**

**console.log(listaDeCompras);**

**// Saída: \["Arroz", "Feijão", "Leite", "Pão"]**



**● Somar números de 1 a 10 usando loop.** 

**let soma = 0;**



**for (let i = 1; i <= 10; i++) {**

  **soma += i; // soma = soma + i**

**}**



**console.log("A soma dos números de 1 a 10 é:", soma);**



**2.7 Reflexão** 

**● Por que conhecer tipos e operadores ajuda a programar melhor?** 

**-> Conhecer tipos e operadores melhora a programação ao permitir a criação de cálculos corretos, comparações precisas e decisões lógicas eficientes, resultando em códigos mais robustos, confiáveis e com melhor gerenciamento de memória.**



**● Por que usar console.log() é importante para debug?** 

**-> É importante para debug porque permite exibir informações e valores de variáveis no console do navegador de forma não bloqueante, ajudando a verificar o fluxo do código, inspecionar dados em diferentes pontos e entender o estado do aplicativo sem interromper o usuário.**



**● Como planejar variáveis, funções e loops antes de programar?** 

**Definindo o objetivo, dividindo o problema em partes menores, planejando o fluxo lógico usando pseudocódigo ou fluxogramas e definindo quais informações serão necessárias (variáveis), quais são os blocos lógicos de processamento (funções) e quais partes do código devem se repetir (loops).** 





