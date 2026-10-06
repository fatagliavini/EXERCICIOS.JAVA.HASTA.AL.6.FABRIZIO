import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
       System.out.println("---EXERCICIO 1---");
       int i = 2;
       while (i <= 100) {
            System.out.println(i);
            i += 2;
        }
        System.out.println("---EXERCICIO 2---");
        int j = 1;
        while (j <= 100) {
            System.out.println(j);
            j += 2;
        }
        int k = 2;
        System.out.println("---EXERCICIO 3---");
        int soma = 0;

        for (int l = 1; l <= 50 ; l++) {
            soma += l;
        }
        System.out.println("A soma dos 50 primeiros números é: " + soma);

        System.out.println("---EXERCICIO 4---");
        Scanner scanner = new Scanner(System.in);
        System.out.print("Digite um número para ver a tabuada: ");
        int numero = scanner.nextInt();
        System.out.println("Tabuada do " + numero + ":");
        for (int m = 1; m <= 10; m++) {
            int resultado = numero * m;
            System.out.println(numero + " x " + m + " = " + resultado);
        }
        System.out.println("---EXERCICIO 5---");
        int n = 106;
        long fatorial = 1;
        for (int o = 1; o <= n; o++) {
            fatorial *= o;
        }
        System.out.println("O fatorial de " + n + " é: " + fatorial);
    }
    System.out.println("---EXERCICIO 6---");
    int edad = 18;
    if (edad >= 18) {
        System.out.println("Você é maior de idade.");
    } else {
        System.out.println("Você é menor de idade.");
    }
}
