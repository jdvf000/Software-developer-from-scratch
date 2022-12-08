Algoritmo BasicCalculator
	Imprimir 'Type a number1'
	Leer number1
	Imprimir 'Type a number2'
	Leer number2
	Imprimir 'Choose the operation +, -, *, /'
	Leer symbol
	Imprimir 'Processing' 
	Segun symbol Hacer
		'+':
			Imprimir 'Outcome:' + '' + ConvertirATexto(number1 + number2)
			Imprimir 'SUMA'
			
		'-':
			Imprimir 'Outcome:' + '' + ConvertirATexto(number1 - number2)
			Imprimir 'RESTA'
		'*' :
			Imprimir 'Outcome:' + '' ConvertirATexto(number1 * number)
			Imprimir 'MULTIPLICAION'
			
		'/' :
			Imprimir 'Outcome:' + '' ConvertirATexto(number1 / number2)
			Imprimir 'DIVISION'
		De Otro Modo 
			Imprimir 'Error, please make sure select numbers only this is a basic caltulator'
	FinSegun
FinAlgoritmo
