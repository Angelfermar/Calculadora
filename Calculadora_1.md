# Calculadora
Simple calculator made with Java.


import java.util.Scanner;

public class Calcultaor {
	public static void main(String[] args) {
		System.out.println("Bienvenido a la calculadora");
		while (true) {
			System.out.println("Introduce tu orden. Suma, resta, multiplicación, división, o cerrar");
			Scanner reader = new Scanner(System.in);
			String orden = reader.nextLine();
	if (orden.equals("cerrar")) {
		break;
	}
	System.out.println("Introduce el primer número");
	int numero = Integer.parseInt(reader.nextLine());
	System.out.println("Introduce el segundo número");
	int numero2 = Integer.parseInt(reader.nextLine());
		
		if (orden.equals("suma"))	{
			int resultado = numero + numero2;
			System.out.println("El resultado es " + resultado);			
		}
		if (orden.equals("resta")) {
			int resultado = numero - numero2;
			System.out.println("El resultado es " + resultado);
					}
		if (orden.equals("multiplicación")) {
			int resultado = numero * numero2;
			System.out.println("El resultado es " + resultado);
		}
		if (orden.equals("división")) {
			int resultado = numero / numero2;
			System.out.println("El resultado es " + resultado);
		}
		}
		System.out.println("Hasta luego");
	}
}



