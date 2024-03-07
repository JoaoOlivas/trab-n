import java.util.Scanner;

public class teste {

 public static void main(String[] args){
 
    try (Scanner scanner = new Scanner(System.in)) {
    
        System.out.println("Digite o numero desejado");
        
        int n = scanner.nextInt();

        int quadrado = n * n;
        int cubo = n * n * n;
        int quadradodoquadrado = n * n * n * n;

        System.out.println("o quadrado de " + n + " é: " + quadrado);
        System.out.println("o cubo de " + n + " é: " + cubo);
        System.out.println("o qquadradodoquadrado de " + n + " é: " + quadradodoquadrado);
    }
 }
  
}
