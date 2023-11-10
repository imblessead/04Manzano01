# 04Manzano01
04Manzano01

package exercicios;

public class Exercicio04Manzano01 {

	public static void main(String[] args) {
	int soma=0;
		for (int i = 1; i < 501; i++) {
			if (i % 2 == 0) {
				soma = soma + i;
			}	
		}
		System.out.println("O valor total da sma e : " + soma);
	} 

}

