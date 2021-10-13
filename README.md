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

> 4. Leia um número real e imprima a quinta parte deste número.
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

>7. Leia uma velocidade em KM/h e apresentente convertida em M/s (metros por segundo) a formula de conversão é M = K/3,6 sendo K a velocidade em km/h e M em m/s.
```
import java.util.Scanner;

public class Exercicio7 {

    public static void main (String[]args){

        double k,m;
        Scanner velocidade = new Scanner(System.in);
        System.out.println("Informe os quilometros por hora: ");
        k = velocidade.nextDouble();

        m = k/3.6;
        System.out.println("A velocidade convertida em m/s é: "+ m);

    }

}
```

>8. Leia uma velocidade em m/s e apresente convertida em km/h. A formula de conversão é: k = m*3,6, sendo K a velocidade e km/h e M em M/s.
```
import java.util.Scanner;

public class Exercicio8 {
    public static void main(String[]args){

            double k,m;
            Scanner velocidade = new Scanner(System.in);
            System.out.println("Informe a velocidade em metros por segundo: ");
            m = velocidade.nextDouble();

            k = m*3.6;
            System.out.println("A velocidade convertida em k/h é: "+ k);

        }

    }
```

>9. Leia uma distância em milhas e apresnete convertida em quilometros. A formula de conversão é: K = 1,61*M, sendo K a distancia em quilometros e M e, milhas.

```
import java.util.Scanner;

public class Exercicio9 {

    public static void main (String[]args){

        double k,m;
        Scanner velocidade = new Scanner(System.in);
        System.out.println("Informe a distância em milhas: ");
        m = velocidade.nextDouble();

        k = 1.61*m;
        System.out.println("A velocidade convertida em quilometros é: "+ k);

    }

}
```

>10. Leia uma distancia em quilometros e apresente convetida em milhas. A fórmula de conversão é M = k/1,61 sendo K a distancia em quilometros e M em milhas.
```
import java.util.Scanner;

public class Exercicio10 {

    public static void main (String[]args){

        double k,m;
        Scanner velocidade = new Scanner(System.in);
        System.out.println("Informe a distância em quilometros: ");
        k = velocidade.nextDouble();

        m = k*1.61;
        System.out.println("A velocidade convertida em milhas é: "+ m);

    }

}
```
>11. Leia um angulo em graus e apresente convertido em radianos. A formula de conversão é: R=G*PI/180, sendo G o angulo em graus e R em radianos e PI=3,14.
>12. Leia um angulo em radianos e apresente o convertido em graus. A formula de conversão é G = R*180/PI, sendo G o angulo em graus e R em radianos e PI = 3.14.
>13. Leia um valor de comprimento em polegadas e apresente convertido em cetimentros. A formula de conversão é C = P*2,54, sendo C o comprimento em cetimentros e P o comprimento em polegadas.
>14. Leia um valor de comprimento em cetimentros e apresente convertido em polegadas. A formula de conversão é P = c/2,54 sendo C o comprimento em cetimentros e P o comprimento em polegadas.
>15. Leia um valor de volume em metros cubicos m² e apresente convertido em litros. A formula de conversão é L=1000*M, sendo L o volume em litros e M o volume em metros cúbicos.
>16. Leia um valor de volume em litros e apresente convertido em metros cúbicos m³. A formula de conversão é M=l/1000 sendo L o volume em litros e M o volume em metros cúbicos.
>17. Leia um valor de massa em quilogramas e apresente convertido em libras. A formula de conversão é: L = K/0,45 sendo K a massa em quilogramas e L a massa em libras.
