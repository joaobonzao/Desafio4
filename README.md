package javaapplication133;

import java.text.DecimalFormat;
import java.util.Scanner;

public class JavaApplication133 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        DecimalFormat decimal = new DecimalFormat("0.00");
        // Declarar variáveis
        int idade;
        // Entrada de dados
        System.out.println("Insira sua idade; ");
        idade = ler.nextInt();
        // Processamento e Saida de dados
        if (idade >= 5 && idade <= 7) {
            System.out.println("Você é da categoria infantil A");
        } else if (idade >= 8 && idade <= 10) {
            System.out.println("Você é da categoria infantil B");
        } else if (idade >= 11 && idade <= 13) {
            System.out.println("Você é da categoria Juvenil A");
        } else if (idade >= 14 && idade <= 17) {
            System.out.println("Você é da categoria Juvenil B");
        } else if (idade >= 18) {
            System.out.println("Você é da categoria ");
        }

    }

}
