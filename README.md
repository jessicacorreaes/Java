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
```
import java.util.Scanner;

public class Exercicio11 {
    public static void main (String[]args){

        double g,r;

        Scanner angulo = new Scanner(System.in);
        System.out.println("Informe um angulo em graus: ");
        g = angulo.nextDouble();

        r = g * (3.14/180);
        System.out.println("O angulo em grau convertido para radiano é:" + r);

    }

}
```

>12. Leia um valor de comprimento em polegadas e apresente convertido em cetimentros. A formula de conversão é C = P*2,54, sendo C o comprimento em cetimentros e P o comprimento em polegadas.
```
import java.util.Scanner;

public class Exercicio12 {

    public static void main(String[]args){

        double c,p;
        Scanner comprimento = new Scanner(System.in);
        System.out.println("Informe o comprimento em polegadas:");
        p = comprimento.nextDouble();
        
        c = p*2.54;
        System.out.println("O comprimento em Centimentros é: " + c);
    }
}
```

>13. Leia um valor de comprimento em cetimentros e apresente convertido em polegadas. A formula de conversão é P = c/2,54 sendo C o comprimento em cetimentros e P o comprimento em polegadas.
```
import java.util.Scanner;

public class Exercicio13 {

    public static void main(String[]args){

        double c,p;
        Scanner comprimento = new Scanner(System.in);
        System.out.println("Informe o comprimento em centimentros:");
        c = comprimento.nextDouble();

        p = c/2.54;
        System.out.println("O comprimento em polegadas é: " + p);
    }
}
```

>14. Leia um valor de volume em metros cubicos m² e apresente convertido em litros. A formula de conversão é L=1000*M, sendo L o volume em litros e M o volume em metros cúbicos.
```
import java.util.Scanner;

public class Exercicio14 {
    public static void main(String[]args){
        double l,m;

        Scanner volume = new Scanner(System.in);
        System.out.println("Informe um valor de volume em metros cubicos m²:");
        m = volume.nextDouble();
        
        l = 1000*m;
        System.out.println("O valor convertido para litros é:" + l);
    }
}
```
>15. Leia um valor de volume em litros e apresente convertido em metros cúbicos m³. A formula de conversão é M=l/1000 sendo L o volume em litros e M o volume em metros cúbicos.
```
import java.util.Scanner;

public class Exercicio14 {
    public static void main(String[]args){
        double l,m;

        Scanner volume = new Scanner(System.in);
        System.out.println("Informe um valor de volume em litros:");
        l = volume.nextDouble();

        m = l/1000;
        System.out.println("O valor convertido para m³ é:" + m);
    }
}
```

>16. Leia um valor de massa em quilogramas e apresente convertido em libras. A formula de conversão é: L = K/0,45 sendo K a massa em quilogramas e L a massa em libras.
```
import java.util.Scanner;

public class Exercicio16 {

    public static void main (String[]args){

        double k,l;
        Scanner massa = new Scanner(System.in);
        System.out.println("Informe um valor de massa em quilogramas: ");
        k = massa.nextDouble();

        l = k/0.45;
        System.out.println("O valor convertido em libras é " + l);
        
    }
}
```
> 17. Leia quatro notas, calcule a media aritmetica e imprima o resultado.
```
import java.util.Scanner;

public class Exercicio17 {
    public static void main(String[]args){
        double n1, n2, n3, n4, media;

        Scanner nota = new Scanner(System.in);
        System.out.println("Informe a primeira nota:");
            n1 = nota.nextDouble();
            nota.nextLine();

        System.out.println("Informe a segunda nota:");
            n2 = nota.nextDouble();
            nota.nextLine();

        System.out.println("Informe a terceira nota:");
            n3 = nota.nextDouble();
            nota.nextLine();

        System.out.println("Informe a quarta nota:");
            n4 = nota.nextDouble();
            nota.nextLine();

        media = (n1 + n2 + n3 + n4) / 4;

        System.out.println("A media das 4 notas é " + media);

    }

}
```

> 18. Leia um valor em real e a cotação do dolar. Em seguida, imprima o valor correspondente em dolares.
```
import java.util.Scanner;

public class Exercicio18 {
    public static void main (String[]args){

        double r,d, convertido;

        Scanner valor = new Scanner(System.in);
        System.out.println("Informe um valor em Real ");
        r = valor.nextDouble();

        System.out.println("A cotação do dolar hoje está R$5,51");
        d = 5.51;

        convertido = r * d;
        System.out.printf("Seu saldo é R$ %.2f", convertido);

    }

}
```
> 19. Leia um número inteiro e imprima o seu antecessor e o seu sucessor.
> 20. Leia um número inteiro e imprima a soma do sucessor de seu triplo com o antecessor de seu dobro.
> 21. Leia o tamanho do lado de um quadrado e imprima como resultado a sua area.
> 22. Faça um programa que leia o valor de um produto e imprima o valor com desconto, tendo em vista que o desconto foi de 12%.
> 23. Leia o salário de um funcionario. Calcule e imprima o valor do novo salario sabendo que  ele recebeu um aumento de 25%.
> 24. (39) A importancia de R$780.000,00 será dividida entre três ganhadores de um concurso.
> Sendo que da quantia total:
> - O primeiro ganhador recebera 46%;
> - O segundo recebera 32%;
> - O terceiro recebera o restante.
> Calcule e imprima a quantia ganha por cada um dos ganhadores.
> 25.  
