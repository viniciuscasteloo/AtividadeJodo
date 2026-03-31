//Atividade1
public class MultiplosDeCinco {
    public static void main(String[] args) {
        for (int i = 1; i <= 500; i++) {
            if (i % 5 == 0) {
                System.out.println(i);
            }
        }
    }
}
//Atividade2
import java.util.Scanner;

public class Main {

public class VerificaCredito {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Número da conta: ");
        int numeroConta = scanner.nextInt();

        System.out.print("Saldo no início do mês: ");
        double saldoInicial = scanner.nextDouble();

        System.out.print("Total de despesas no mês: ");
        double despesas = scanner.nextDouble();

        System.out.print("Total de créditos no mês: ");
        double creditos = scanner.nextDouble();

        System.out.print("Limite de crédito: ");
        double limiteCredito = scanner.nextDouble();

        double novoSaldo = saldoInicial + despesas - creditos;

        System.out.println("\nConta: " + numeroConta);
        System.out.println("Novo saldo: " + novoSaldo);

        if (novoSaldo > limiteCredito) {
            System.out.println("Limite de crédito excedido");
        }

        scanner.close();
    }
}
//Atividade3
