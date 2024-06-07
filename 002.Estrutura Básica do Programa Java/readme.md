# Estrutura Básica de um Programa Java: Entendendo nosso Primeiro Programa Java "Hello World"

## Estrutura Básica de um Programa Java

```
package com.company; // Agrupa classes
public class Main {   // Ponto de entrada da aplicação
    public static void main(String[] args) {
        System.out.println("Olá Mundo");
    }
}
```

## Funcionamento do programa "Hello World" mostrado acima:

### 1. package com.company:
- Pacotes são usados para agrupar classes relacionadas.
- A palavra-chave "package" é usada para criar pacotes em Java.
- Aqui, com.company é o nome do nosso pacote.

### 2. public class Main:
- Em Java, todo programa deve conter uma classe.
- O nome do arquivo e o nome da classe devem ser iguais.
- Aqui, criamos uma classe chamada "Main".
- É o ponto de entrada da aplicação.

### 3. public static void main(String[] args) {...}:
- Este é o método main() do nosso programa Java.
- Todo programa Java deve conter o método main().

### 4. System.out.println("Olá Mundo"):
- O código acima é usado para exibir a saída na tela.
- Qualquer coisa passada dentro das aspas é impressa na tela como texto simples.

### 5. Convenções de Nomenclatura
- Para classes, usamos a Convenção Pascal. A primeira e as subsequentes letras de uma palavra são maiúsculas (uppercase).
- Exemplo: Main, MyScanner, MyEmployee, CodeWithHarry
- Para funções e variáveis, usamos a Convenção camelCase. Aqui, a primeira letra é minúscula, e as subsequentes são maiúsculas, como myScanner, myMarks, CodeWithHarry

### Notas Manuscritas: [Clique para Baixar](https://api.codewithharry.com/media/videoSeriesFiles/courseFiles/java-tutorials-for-beginners-2/IntroToJava.pdf)

### Folha de Dicas Definitiva do Java: [Clique para Baixar](https://api.codewithharry.com/media/videoSeriesFiles/courseFiles/java-tutorials-for-beginners-2/UltimateJavaCheatSheet.pdf)