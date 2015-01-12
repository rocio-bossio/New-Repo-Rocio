import java.util.Scanner;

public class numbers {
public static void main(String[] args) {     
	Scanner sc = new Scanner(System.in);
	int Numero1;   
    int Numero2; 
    int suma;
	System.out.print("Introduzca un número entero: ");
	Numero1 = sc.nextInt();
    System.out.print("Introduzca un número entero: ");
    Numero2 = sc.nextInt();
    suma = Numero1 + Numero2;
    System.out.println("Resultado de la suma " + suma);	
}

}
