![java-icon](https://user-images.githubusercontent.com/40298927/174925141-07490c3f-d64f-4db3-b6b5-e32329127264.png) 

Capítulo 03 | Fundamentos da linguagem

<p> Na base de qualquer linguagem de programação estão seus tipos de dados e operadores, e JAVA não é uma exceção. Esses elementos definem os limites de uma linguagem e determina o tipo de tarefas às quais ela pode ser aplicada dentro de um sistema/aplicação. Os tipos de dados são especialmente importantes em JAVA porque a mesma é considerada uma linguagem fortemente tipada.</p>

<p> A variável pode ser definida como um recurso das linguagens de programação utilizado para armazenar valores em memória. Dessa forma sempre que precisarmos obter esse valor, basta referenciarmos. </p> 

**`Tipos Primitivos`**

![Capturar_select-area_20221207220550](https://user-images.githubusercontent.com/40298927/206331060-292042e1-6b49-4528-80c3-3e33869e6c10.png)

Vale ressaltar que o termo **primitivo** é usado para indicar que esses tipos não são de objetos no sentindo de Orientação Objeto e sim valores binários comuns.

**`Tipos Inteiro`**

No Java é definido quatro tipos inteiros: conforme apresentado na imagem a seguir: 

![Capturar_select-area_20221207225106](https://user-images.githubusercontent.com/40298927/206336611-1331e2da-2967-41e2-a9c6-226af7e7f37a.png)

O tipo inteiro mais usado é **int**. Variáveis de tipo int costumam ser empregadas no controle de laços, na indexação de arrays e na execução de cálculos inteiros para fins gerais.  

**`Tipos de ponto flutuante`**

Os tipos de ponto flutuante podem representar números que têm componentes fracionários. Há dois tipos de ponto flutuante, **float** e **double**, que representam números de precisão simples e dupla, respectivamente. 

 ![Capturar_select-area_20221207225119](https://user-images.githubusercontent.com/40298927/206336630-a7841181-ae77-43ac-972b-3e82df2fa998.png)

De ambos, o double é mais usado, porque todas as funções matemáticas da biblioteca de classe Java usam valores double. 

Podemos conferir alguns exemplos de **`operações matemáticas/operadores aritméticos`** utilizando os tipos de variáveis do Java. 

![Capturar_select-area_20230206231842](https://user-images.githubusercontent.com/40298927/217131167-a788b64b-6322-416f-9953-ecd6b530d359.png)

Após entendermos sobre os tipo primitivos e como os operadores ariméticos são aplicado no Java, a leitura a seguir irá abordar sobre **escopo de variável**.

O escopo de variável pode ser definido como um ambiente onde uma determinada variável pode ser acessada. No Java, o escopo de variáveis vai de acordo com o bloco onde a mesma foi declara. 

Vale ressaltar que quando falamos de bloco estamos falando uma espaço delimitado com inicio e fim, conforme apresentado na imagem a seguir:

![Capturar_select-area_20230211214823](https://user-images.githubusercontent.com/40298927/218287415-86709b44-08f0-4eee-bfd8-ff06fc5475de.png)

Dito isso, imagine uma variavel criada dentro de um bloco, a mesma se torna inacessível interpretador sair do bloco de execução, ao qual ela pertence. Com isso esta variável não pode ser lida ou manipulada por rotinas e códigos que estão fora do seu bloco de declaração, ou seja, fora do escopo da variável.

Em uma Classe, podemos visualizar a diferença de escopos. Os atributos (variáveis) são declarados no corpo principal da Classe, sendo portanto, acessíveis por todos os métodos.

Caso você declare uma variável **dentro do método**, o escopo dessa variável está limitado apenas ao corpo desse método, ou seja, dentro das chaves que limitam o método.

![Capturar_select-area_20230211223803](https://user-images.githubusercontent.com/40298927/218288437-307fb3a3-4742-45a7-bfe6-c1f2da0c33e6.png)

**`Entrada de dados`**

Considerando-se que você precisa que o usuário responda um questionário que irá apresentar na tela. Nos deparamos com a seguinte pergunta: Como ler o valor que o usuário digitou em seu teclado? A resposta está na utilização da **Classe Scanner do Java.**    

Na linguagem Java, a partir do Java 1.5 ou Java 5.0, o pacote de classes **java.util** disponibilizou a classe Scanner, que implementa operações de entrada de dados pelo teclado.

A classe Scanner possui vários métodos que possibilitam a entrada de dados de 
diferentes tipos, entre eles destacam-se:

**`String next()`** - retorna uma cadeia de caracteres simples, ou seja, que não usa o caractere espaço em branco;

**`double nextDouble()`** - retorna um número em notação de ponto flutuante normalizada em precisão dupla de 64 bits (usado para receber valores reais ou monetários);

**`boolean hasNextDouble()`** - retorna true se o próximo dado de entrada pode ser interpretado como um valor double;

**`int nextInt()`** - retorna um número inteiro de 32 bits;

**`boolean hasNextInt()`** - retorna true se o próximo dado de entrada pode ser interpretado como um valor int;

**`String nextLine()`** - retorna uma cadeia de caracteres, por exemplo: “BlogJava”;

**`long nextLong()`** - retorna um número inteiro de 64 bits.

A seguir podemos vê na prática como podemos utilizar do recurso da Classe Scanner: 

![Capturar_select-area_20230219204710](https://user-images.githubusercontent.com/40298927/219985252-f0ec524c-1923-441d-801c-5d56e5c6cac9.png)

**`Palavras Reservadas`**

![Capturar_select-area_20230302193819](https://user-images.githubusercontent.com/40298927/222576222-ec5e972f-0676-48d4-8493-1d0980caf487.png)

![Capturar_select-area_20230302193909](https://user-images.githubusercontent.com/40298927/222576237-f8bb3f37-9a67-4d81-9edc-3772fe28f9c9.png)


_Fontes: - Book Começando a Programar em Java para Leigos; Book Java para Iniciantes; Vídeos aulas Isiflix_

:[👈] <a href="https://github.com/agathapaiiva/blog-java/blob/0e736414432447d6e26f0ab5a69d34dc20f478a5/README.md"> voltar para página anterior </a>
