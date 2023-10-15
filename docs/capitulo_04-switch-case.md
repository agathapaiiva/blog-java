![java-icon](https://user-images.githubusercontent.com/40298927/174925141-07490c3f-d64f-4db3-b6b5-e32329127264.png) 

Capítulo 04 | Iremos aprender sobre:

**`SWITCH CASE`**

A instrução **SWITCH** fornece uma ampla ramificação com vários caminhos. Logo, ela permite que o programa faça uma seleção entre várias alternativas. 

~~~exemplo
SWITCH(EXPRESSÃO){
    CASE CONSTANTE 1:
        sequência de instruções
        BREAK;
    CASE CONSTANTE 2:
        sequência de instruções
        BREAK;
     CASE CONSTANTE 3:
        sequência de instruções
        BREAK;
    DEFAULT:
     sequência de instruções
}
~~~

Como podemos verificar a estrutura switch se inicia através de uma expressão o qual é verificada sucessivamente em uma lista de constante. Quando uma ocorrência é encontrada a seuqência de instruções associada a essa ocorrência é executada. Vamos analisar o exemplo a seguir:

~~~java
import java.util.Scanner;

public class MainTest {
    public static void main(String[] args) {
        
        Scanner scanner = new Scanner(System.in);
        System.out.println("Digite uma letra do tipo vogal:");
        String vogal = scanner.next();

        switch (vogal.toUpperCase()){
            case "A":
                System.out.println("Você digitou a vogal A");
                break;
            case "E":
                System.out.println("Você digitou a vogal E");
                break;
            case "I":
                System.out.println("Você digitou a vogal I");
                break;
            case "O":
                System.out.println("Você digitou a vogal O");
                break;
            case "U":
                System.out.println("Você digitou a vogal U");
                break;
            default:
                System.out.println("Você digitou uma letra que não representa as vogais");
        }
        scanner.close();
    }
}
~~~

**Resultado do Código || CASE**

![Alt text](/docs//imgs/image-1.png)

**Resultado do Código || DEFAULT**

![Alt text](/docs//imgs/image-3.png)

Alguns pontos deve ser considerados:
* Cada valor especificado nas instruções **case** deve ser uma expressão de constante exclusiva. Não são permitidos valores duplicado em **case**;
* A sequência de instruções **default** é executada quando nenhuma constante case coincide com a expressão >> *no exemplo apresentado: quando alguma letra do tipo consoante for digitada*;
* A instrução **default** é opcional, se não estiver presente, não ocorrerá nenhuma ação quando todas as comparações falharem. 

Quando uma ocorrência é encontrada, as instruções associadas a esse **case** são  executadas até o **break** ser alcançado ou, no caso **default** ou do último  case, até  o fim de  switch seralcançado.    

_Fontes: Vídeos aulas Isiflix_ e https://dicasdeprogramacao.com.br/

:[👈] <a href="https://github.com/agathapaiiva/blog-java"> voltar para página anterior </a>