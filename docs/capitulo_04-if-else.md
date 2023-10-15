![java-icon](https://user-images.githubusercontent.com/40298927/174925141-07490c3f-d64f-4db3-b6b5-e32329127264.png) 

Capítulo 04 | Iremos aprender sobre:

**`IF e ELSE`**

Quando você está trabalhando com programas de computador, é muito comum construir tomadas de decisão, na linguaguém JAVA não seria diferente o recurso de desvio é conhecido ou chamada de instrução **IF/ELSE** vamos analisar o exemplo a seguir:

~~~exemplo
IF (CONDIÇÃO){
    SEQUÊNCIA DE INSTRUÇÕES
}ELSE{
    SEQUÊNCIA DE INSTRUÇÕES
}
~~~

Se a expressão condicional for verdadeira, o alvo de **IF** será executado, caso contrário, se houver, o alvo de **ELSE** será executado. Nunca ambos serão executados. A expressão condicional que controla IF deve produzir um resultado **BOOLEAN**.

~~~java
import java.util.Scanner;

public class InstrucaoIF {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        double nota1, nota2, media;

        System.out.println("Digite a N1:");
        nota1 = scanner.nextDouble();

        System.out.println("Digite a N2:");
        nota2 = scanner.nextDouble();

        media = (nota1 + nota2) / 2;
        System.out.println("A média é: " + media);

        //BLOCO de IF/ELSE 

        if(media >= 7){
            System.out.println(media + " >> APROVADO");
        }else{
              System.out.println(media + " >> REPROVADO");
        }
        scanner.close();
    }
}
~~~

**Resultado do Código || APROVADO**

![Alt text](/docs//imgs/image.png)

**Resultado do Código || REPROVADO**

![Alt text](/docs//imgs/image-2.png)


**`IF's ANINHADOS OU ENCADEADOS`**

Existe situações aonde é necesário ter IF's encadeados. Na linguém JAVA é o fato de que uma estrução **ELSE** será sempre referente à instrução **IF** mais próxima que estiver dentro do mesmo bloco.

~~~java
import java.util.Scanner;

public class InstrucaoIF {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);
        int a, b, c;

        System.out.println("Digite valor de A:");
        a = scanner.nextInt();

        System.out.println("Digite valor de B:");
        b = scanner.nextInt();

        System.out.println("Digite valor de C:");
        c = scanner.nextInt();

        if(a == b){
            System.out.println("o valor de B é igual de A: " + a);
           } else if(a == c) {
            System.out.println( "o valor de C é igual de A: " + a);
        }else {
            System.out.println( "o valor de B é diferente de A: " + a);
        }
        scanner.close();
    }
}
~~~
>
>"As expressões condicionais são avaliadas de cima para baixo. Assim que uma condição verdadeira é encontrada, a instrução associada a ela é executada e o resto da escada 
>é ignorado. Se nenhuma das condições for verdadeira, a instrução **ELSE** final será  executada. Com frequência, o **ELSE** final age como uma condição padrão, isto é, se todos
>as outras condicionais falharem, a última instrução **ELSE** será executada. Se  não houver um **ELSE** final as outras condições forem falsas, não ocorrerá nenhuma ação."
>
> [Livro Java para iniciantes 6ª Edição]

_Fontes: Vídeos aulas Isiflix_ e Livro Java para iniciantes 6ª Edição

:[👈] <a href="https://github.com/agathapaiiva/blog-java/blob/0e736414432447d6e26f0ab5a69d34dc20f478a5/README.md"> voltar para página anterior </a>

