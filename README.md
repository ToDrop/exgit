# exgit

package aula2;

import javax.swing.JOptionPane;

public class NumeroPrimo {

	public static void main(String[] args) {
		// Número primo é divisível por 1 e por ele mesmo (Somented!)
		// A quantidade de divisores é sempre 2.
		
		int nprimo;
		int ndivisor = 1;
				
		String r = JOptionPane.showInputDialog(null, "Digite um número ");
		nprimo = Integer.parseInt(r);
		
		for (nprimo = 1; nprimo <= ndivisor; nprimo++) {
			
		if (nprimo % ndivisor == 0) {
		System.out.println ("O número é primo ");
		}
		
		else {
		System.out.println("O número não é primo ");
		}

	}

	}
		
}
