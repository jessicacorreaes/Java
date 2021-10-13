# Java Exercicios

> 1. Faça um programa que leia um número inteiro e o imprima.
```
import java.util.Scanner;

public class Exercicio1 {

    public static void main (String[]args){
        int n;

        Scanner numero = new Scanner(System.in);
        System.out.println("digite um número: ");
        n = numero.nextInt();

        System.out.println("O número digitado foi: " + n);

    }
}
```

> 2. Peça ao usuario para digitar três valores inteiros e imprima a soma deles.
```
import java.util.Scanner;

public class Exercicio2 {

    public static void main(String[]args){
        int n1, n2, n3;
        int soma;

        Scanner numero = new Scanner(System.in);
        System.out.println("Digite o primeiro número: ");
        n1 = numero.nextInt();
        numero.nextLine();
        System.out.println("Digite o segundo número: ");
        n2 = numero.nextInt();
        numero.nextLine();
        System.out.println("Digite o terceiro número: ");
        n3 = numero.nextInt();

        soma = n1+n2+n3;

        System.out.println("A soma dos números é: " + soma);

    }
}
```

> 3. Leia um número real e imprima o resultado do quadrado desse número.
```
import java.util.Scanner;

public class Exercicio3 {
        public static void main(String[]args){

            int n,quadrado;

            Scanner numero = new Scanner(System.in);
            System.out.println("Digite um número para que possamos elevar ao quadrado: ");
            n = numero.nextInt();
            quadrado = n*n;

            System.out.println("O quadrado do número que você digitou é: " + quadrado);


        }
}
```

4. Leia um número real e imprima a quinta parte deste número.
```
import java.util.Scanner;

public class Exercicio4 {

    public static void main(String[]args){

        int n, parte;
        Scanner numero = new Scanner(System.in);
        System.out.println("Informe um número para calcularmos a quinta parte dele: ");
        n = numero.nextInt();

        parte = n/5;

        System.out.println("A quinta parte de " + n + " é: "+ parte);

    }
}
```

>5.Leia uma temperatura em graus Celcius e apresente-a convertida em graus Fahrenheit A formula de conversão é: F = C*(9.0/5.0)+32.0, sendo F a temperatura em Farenheit e C a temperatura em Celcius.
```
import java.util.Scanner;

public class Exercicio5 {

    public static void main(String[]args){
        double C, F;

        Scanner temperatura = new Scanner(System.in);
        System.out.println("Informe a temperatura em Celsius na sua cidade agora?");
        C = temperatura.nextDouble();
        F = C*(9.0/5.0)+32.0;

        System.out.println("A temperatura convertida em Farenheit é: " + F);


    }
}
```

>6. Leia uma temepratura em graus Fahrenheit e apresente-a convertida em graus Celsius. A formula de conversão é: C = 5.0*(F-32.0)/9.0, sendo C a temperatura em Celsius e F a temperatura em Fahrenheit.
```
import java.util.Scanner;

public class Exercicio6 {

    public static void main(String[]args){
        double C, F;

        Scanner temperatura = new Scanner(System.in);
        System.out.println("Informe a temperatura em Celsius na sua cidade agora?");
        F = temperatura.nextDouble();
        C = 5.0*(F-32.0)/9.0;

        System.out.println("A temperatura convertida em Farenheit é: " + C);


    }
}
```

7. Leia uma velocidade em KM/h e apresentente convertida em M/s (metros por segundo) a formula de conversão é M = K/3,6 sendo K a velocidade em km/h e M em m/s.
