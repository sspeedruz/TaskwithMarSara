import java.util.Scanner;

public class Waves {

public static void main (String [] args) {
        
        Scanner scan = new Scanner(System.in);
        int wavelength = scan.nextInt();
        int numberOfWaves = scan.nextInt();
        scan.close();
        
        System.out.println("*");
        
    for(int a=1; a<=numberOfWaves; a++) {
        
        for(int i=2; i<=wavelength; i++) {
            for(int z=1; z<i; z++) {
                System.out.print(" ");
            }
            System.out.println("*");
        }
        
        for(int i=wavelength-1; i>0; i--) {
            for(int z=1; z<i; z++) {
                System.out.print(" ");
            }
            System.out.println("*");
        }
        
    }
}
}
