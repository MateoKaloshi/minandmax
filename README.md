package FindMaxAndMin;

import java.util.Scanner;

public class FindMaxAndMin {

	public static void main(String[] args) {
	     
		Scanner scan = new Scanner(System.in);
		
		System.out.print("Vendos Numrin: ");
		
		int a;
		int b = scan.nextInt();
		int max = Integer.MIN_VALUE;
		int min = Integer.MAX_VALUE;
		
		for(int i = 0; i < b; i++) {
			a = scan.nextInt();
			if(a > max) {
				max = a;
			}
			if(a < min) {
				min = a;
			}
		}
		
		System.out.print("Minimumi eshte: " + min + "\n" + "Maximumi eshte: " + max);
		scan.close();

	}

}
