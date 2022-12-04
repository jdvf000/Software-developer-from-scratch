# Software-developer-from-scratch
======================================================================

November 30 2022 
Pseint: 
Modulo = El residuo.
% = Symbol

Even = 0
Odd = 1

** EVEN & ODD
Algoritmo evenAndOdd
	Leer N
	Imprimir N % 2
FinAlgoritmo


** ODD & EVEN
Algoritmo detectEvenOdd
	Imprimir 'Ingrese número a verificar'
	Leer x
	Si x % 2 == 0 Entonces
		Imprimir 'Número: ' + ConvertirATexto(x) + ' es par'
	SiNo
		Imprimir 'Número: ' + ConvertirATexto(x) + ' es impar'
	FinSi
FinAlgoritmo

==========================================================================

** REGISTER A FORM
** USER FORM 
Algoritmo userForm
	Imprimir '==== User From ====' 
	Imprimir 'First name'
	Leer firstName
	
	Imprimir 'Last Name'
	Leer lastName
	
	Imprimir 'Age'
	Leer age
	
	Imprimir 'Email address'
	Leer emailAddress
	
	Imprimir 'Full address'
	Leer fullAddress
	
	Imprimir '---- 
User Data ----'
	Imprimir 'Full name: '+ firstName + ' ' + lastName
	Imprimir 'Age: ' + age
	Imprimir 'Email address: ' + emailAddress
	Imprimir ' Full Address: ' + fullAddress
	Imprimir '---------------'
FinAlgoritmo
