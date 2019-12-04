# letraaleatoria
Sacar letras aleatorias y decir si son consonantes o vocales
package letraAleatoria;

public class letraAleatoria {

	public static void main(String[] args){

		char car;
		boolean consonante;
		car = (char)(Math.random( ) * 26 + 'A');
		
		//Utilizando el operador condicional
		String resultado = (car == 'A' || car == 'E' || car == 'I' || car == 'O' || car == 'U') ?
		"VOCAL" : "CONSONANTE";
		System.out.println(car+" es "+resultado);
		
		car = (char)(Math.random( ) * 26 + 'A');
		resultado = (car == 'A' || car == 'E' || car == 'I' || car == 'O' || car == 'U') ? "VOCAL"
		: "CONSONANTE";
		System.out.println(car+" es "+resultado);
		
		car = (char)(Math.random( ) * 26 + 'A');
		resultado = (car == 'A' || car == 'E' || car == 'I' || car == 'O' || car == 'U') ? "VOCAL"
		: "CONSONANTE";
		System.out.println(car+" es "+resultado);
		}
}
