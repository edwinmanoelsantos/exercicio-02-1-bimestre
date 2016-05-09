# exercicio-02-1-bimestre

//faça um programa que peça um valor e mostre na tela se o valor é positivo ou negativo.
import java.util.Scanner;

public class Exercicio02 {

	public static void main(String[] args) {
		Scanner teclado = new Scanner(System.in);
		System.out.println("Informe um valor:");
		int valor = teclado.nextInt();
		if(valor > 0){
			System.out.println("o valor informado é positivo!!!");
		}else if(valor < 0){
			System.out.println("o valor informado é negativo!!!");
		
		}else if (valor == 0){
			System.out.println("o valor informado é neutro!!!");
		}

	}

}
