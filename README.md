# Proyecto Final Isi
trabajo 

Danilo Enrique Molina Chavarria
Grupo 4 

-Algoritmo en Pseint:

Algoritmo  temperatura
	definir temp como real;
	escribir "ingrese su temperatura:";
	leer temp;
	
	si temp < 30 o temp > 45 entonces;
		escribir "Error: Valor Imposible";
	SiNo
		si temp < 37 Entonces
			escribir "Normal";
	    sino 
			si temp >= 37 y temp <= 38 entonces;
				escribir "Fiebre Leve";
			sino 
				escribir "Fiebre Alta";
			FinSi
		FinSi
	FinSi
FinAlgoritmo


-Algoritmo:

Algoritmo cajero
	definir saldo, retiro Como Entero
	//saldo inicial
	saldo <- 1000
	escribir "Ingrese cantidad a retirar:";
	leer cantidad;
	
	//verificar si es multiplo de 10
	
	si cantidad MOD 10 <> 0 entonces 
		escribir "Error: La cantidad debe ser multiplo de 10"
		
	sino 
		//verificar si hay saldo insuficiente 
		
		si cantidad >= saldo entonces 
			escribir "Error: saldo insuficiente"
			
		sino 
			saldo <- saldo - cantidad 
			escribir "Retiro Exitoso";
		FinSi
	FinSi
	
FinAlgoritmo

