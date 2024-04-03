Algoritmo sin_titulo
	Definir N1, N2, resultado Como Real;
	Definir eleccion Como entero;
	Escribir " Ingrese el primer nùmero " sinsaltar;
	Leer N1;
	Escribir " Ingrese el segundo nùmero " sinsaltar;
	Leer N2;
	Escribir " Escoja una operacion: ";
	escribir "1. Suma";
	escribir "2. Resta";
	escribir "3. Multiplicaciòn";
	escribir "4. Divisiòn";
	leer eleccion;
	Segun eleccion Hacer
		1: 
			resultado = N1 + N2;
			Escribir"La suma es: ", resultado;
		2:
			resultado = N1 - N2;
			Escribir "La resta es: ", resultado;
		3:  
			resultado = N1 * N2;
			Escribir "La multiplicaciòn es: ", resultado;
		4:  
			si N2 == 0 Entonces
				escribir " No se puede realizar la operaciòn ";
			sino resultado = N1 / N2;
				Escribir  "La divisiòn es: ", resultado;
			FinSi
		De Otro Modo:
			escribir " corrija la opciòn seleccionada: ";
	FinSegun
FinAlgoritmo
