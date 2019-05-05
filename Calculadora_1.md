# Calculadora
Simple calculator made with Java.

import java.util.Scanner;
class introducirdosnumeros {
	static void introducedos() {
			}
}
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
	else if (orden.equals("suma"))	{
			System.out.println("Introduce el primer número");
			int numero = Integer.parseInt(reader.nextLine());
			System.out.println("Introduce el segundo número");
			int numero2 = Integer.parseInt(reader.nextLine());
			int resultado = numero + numero2;
			System.out.println("El resultado es " + resultado);			
		}
	else if (orden.equals("resta")) {
			System.out.println("Introduce el primer número");
			int numero = Integer.parseInt(reader.nextLine());
			System.out.println("Introduce el segundo número");
			int numero2 = Integer.parseInt(reader.nextLine());
			int resultado = numero - numero2;
			System.out.println("El resultado es " + resultado);
					}
	else if (orden.equals("multiplicación")) {
			System.out.println("Introduce el primer número");
			int numero = Integer.parseInt(reader.nextLine());
			System.out.println("Introduce el segundo número");
			int numero2 = Integer.parseInt(reader.nextLine());
			int resultado = numero * numero2;
			System.out.println("El resultado es " + resultado);
		}
	else if (orden.equals("división")) {
			System.out.println("Introduce el primer número");
			int numero = Integer.parseInt(reader.nextLine());
			System.out.println("Introduce el segundo número");
			int numero2 = Integer.parseInt(reader.nextLine());
			int resultado = numero / numero2;
			System.out.println("El resultado es " + resultado);
		}
		else {
			System.out.println("Orden no reconocida");
		}
		}
		System.out.println("Hasta luego");
	}
}




