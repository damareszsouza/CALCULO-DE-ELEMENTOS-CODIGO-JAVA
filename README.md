# CALCULO-DE-ELEMENTOS-CODIGO-JAVA

A resposta correta é:
Complete o programa abaixo, arrastando e soltando os trechos de código nos espaços em branco, de forma que o bloco que falta coloque na variável quant a quantidade de elementos em matriz que estão entre 15 e 20.



public class VerificaMatriz {
	public static void main(String[] args) {
		int[][] matriz = new int[3][5];
		
		for(int linha = 0; linha < matriz.length; linha++) { 
			for(int coluna = 0; coluna < matriz[linha].length; coluna++) {
				System.out.printf("matriz[%d][%d]: ", linha, coluna);
				matriz[linha][coluna] = Integer.parseInt(System.console().readLine());
			}
		}
		
		int quant = 0;
		[for(int linha = 0; linha < matriz.length; linha++)] {
			[for(int coluna = 0; coluna < matriz[linha].length; coluna++)] {
				[if(matriz[linha][coluna] >= 15 && matriz[linha][coluna] <= 20)]
					[quant++;]
			}
		}
		
		System.out.printf("\nA MATRIZ POSSUI %d ELEMENTOS ENTRE 15 E 20.\n", quant);
	}
}
