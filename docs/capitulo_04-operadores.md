![java-icon](https://user-images.githubusercontent.com/40298927/174925141-07490c3f-d64f-4db3-b6b5-e32329127264.png) 

Capítulo 04 | Iremos aprender sobre:

**`Operadores Lógicos`**

As operações lógicas trabalham sobre valores booleanos verdadeiro ou falso, tanto os valores de entrada como os valores de saída são desse tipo. Com isso temos os seguintes operadores lógicos: **E, OU, NÃO, NÃO-E, NÃO-OU, OU-EXCLUSIVO E NÃO-OU-EXCLUSIVO**

**`OPERADOR AND "E"`** : O Operador “**E**” ou “**AND**” resulta em um valor **VERDADEIRO** se os dois valores de entrada da operação forem **VERDADEIROS**, caso contrário o resultado é **FALSO**. Abaixo a tabela-verdade da operação **E**.

| VALOR 1           | VALOR 2          | OPERAÇÃO E |
| :---------------- | :----------------| :--------- |
| VERDADEIRO        |  VERDADEIRO      | VERDADEIRO |
| VERDADEIRO        |  FALSO           | FALSO      |
| FALSO             |  VERDADEIRO      | FALSO      | 

***

**`OPERADOR OR "OU"`** : O Operador “**OU**” ou “**OR**” resulta em um valor **VERDADEIRO** se ao menos **UM** dos dois valores de entrada da operação for **VERDADEIRO**, caso contrário o resultado é **FALSO**. Abaixo a tabela-verdade da operação **OU**.

| VALOR 1           | VALOR 2          | OPERAÇÃO OU |
| :---------------- | :----------------| :--------- |
| VERDADEIRO        |  VERDADEIRO      | VERDADEIRO |
| VERDADEIRO        |  FALSO           | VERDADEIRO |
| FALSO             |  VERDADEIRO      | VERDADEIRO | 
| FALSO             |  FALSO           | FALSO      | 

***

**`OPERADOR NOT "NÃO"`** : O Operador “**NÃO**” ou “**NOT**” é o único operador que recebe como entrada apenas um valor, e sua função é simplesmente inverter os valores. Ou seja, se o valor de entrada for **VERDADEIRO**, o resultado será **FALSO** e se o valor de entrada for FALSO, o resultado será **VERDADEIRO**. Abaixo a tabela-verdade da operação **NÃO**.

| VALOR 1           | OPERAÇÃO NÃO
| :---------------- | :----------------
| VERDADEIRO        |  FALSO      
| FALSO             |  VERDADEIRO  

***

**`OPERADOR NAND "NÃO-E"`** : O Operador “**NÃO-E”** ou “**NAND**” é o contrário do operador E (**AND**), ou seja, resulta em **VERDADEIRO**, se ao menos um dos dois valores for **FALSO**, na verdade este é o operador E (**AND**) seguido do operador NÃO (**NOT**). Abaixo a tabela-verdade da operação NÃO-E.

| VALOR 1           | VALOR 2          | OPERAÇÃO NAND |
| :---------------- | :----------------| :--------- |
| VERDADEIRO        |  VERDADEIRO      | FALSO      |
| VERDADEIRO        |  FALSO           | VERDADEIRO |
| FALSO             |  VERDADEIRO      | VERDADEIRO | 
| FALSO             |  FALSO           | VERDADEIRO | 
 

***

**`OPERADOR NOR "NÃO-OU"`** : O Operador “**NÃO-OU**” ou “**NOR**” é o contrário do operador OU (**OR**), ou seja, resulta em **VERDADEIRO**, se os dois valores forem **FALSO**, na verdade este é o operador OU (OR) seguido do operador NÃO (**NOT**). Abaixo a tabela-verdade da operação NÃO-OU.

| VALOR 1           | VALOR 2          | OPERAÇÃO NOR |
| :---------------- | :----------------| :--------- |
| VERDADEIRO        |  VERDADEIRO      | FALSO      |
| VERDADEIRO        |  FALSO           | FALSO      |
| FALSO             |  VERDADEIRO      | FALSO      | 
| FALSO             |  FALSO           | VERDADEIRO | 


***

**`OPERADOR XOR "OU-EXCLUSIVO"`** : O Operador “**OU-EXCLUSIVO**” ou “**XOR**” é uma variação interessante do operador OU (**OR**), ele resulta em VERDADEIRO se apenas um dos valores de entrada for **VERDADEIRO**, ou seja, apenas se os valores de entrada forem **DIFERENTES**. Abaixo a tabela-verdade da operação OU-EXCLUSIVO.

| VALOR 1           | VALOR 2          | OPERAÇÃO XOR |
| :---------------- | :----------------| :--------- |
| VERDADEIRO        |  VERDADEIRO      | FALSO      |
| VERDADEIRO        |  FALSO           | VERDADEIRO |
| FALSO             |  VERDADEIRO      | VERDADEIRO | 
| FALSO             |  FALSO           | FALSO      | 


***

**`OPERADOR XNOR "NÃO-OU-EXCLUSIVO"`** : O Operador “NÃO-OU-EXCLUSIVO” ou “**XNOR**” é o contrário do operador OU-EXCLUSIVO (XOR), ou seja, resulta VERDADEIRO se os valores de entrada forem IGUAIS. Observe a tabela abaixo:

| VALOR 1           | VALOR 2          | OPERAÇÃO XNOR |
| :---------------- | :----------------| :--------- |
| VERDADEIRO        |  VERDADEIRO      | VERDADEIRO |
| VERDADEIRO        |  FALSO           | FALSO      |
| FALSO             |  VERDADEIRO      | FALSO      | 
| FALSO             |  FALSO           | VERDADEIRO |

Agora que você entendeu a tabela verdade, podemos citar os **operadores lógicos** utilizamos na linguagem JAVA, lembrando que cada linguagem tem a sua variação de representatividade dos operadores citados: 

| OPERADOR  | NOME                           | DESCRIÇÃO |
| :-------- | :------------------------------| :--------- |
| &         |  E lógico                      | Retorna true se ambos os operandos forem verdadeiros. |
| ❌         |  OU lógico                     | Retorna true se pelo menos um dos operandos for verdadeiro. |
| ^         |  XOR (OU exclusivo)            | Retorna true se apenas um dos operandos for verdadeiro. | 
| &&        |  E lógico em curto-circuito    | Retorna true se ambos os operandos forem verdadeiros. |
| ❌         |  OU lógico em curto circuito   | Retorna true se pelo menos um dos operandos for verdadeiro.|
| !         |  NÃO lógico                    | Retorna false caso o operando seja avaliado como verdadeiro, ou true se for falso. |

**Uma observação da tabela de operadores lógicos:**
* Símbolo do operadore OU lógico é |  
* Símbolo do operador OU lógico em curto circuito é || 

***

Agora iremos aprender sobre os **Operadores Relacionais** ou de comparação como também é conhecido: 

| OPERADOR  | NOME             | DESCRIÇÃO |
| :-------- | :----------------| :--------- |
| ==        |  IGUAL Á         | Retorna true se os operandos forem iguais |
| !=        |  DIFERENTE       | Retorna true se os operandos são diferentes |
| >         |  MAIOR           | Retorna true se o operando à esquerda for maior que o da direita | 
| <         |  MENOR           | Retorna true se o operando à esquerda for menor que o da direita |
| <=        |  MENOR OU IGUAL  | Retorna true se o operando à esquerda for menor ou igual ao da direita |
| >=        |  MAIOR OU IGUAL  | Retorna true se o operando à esquerda for maior ou igual ao da direita |

_Fontes: Vídeos aulas Isiflix_ e https://dicasdeprogramacao.com.br/

:[👈] <a href="https://github.com/agathapaiiva/blog-java"> voltar para página anterior </a>