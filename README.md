# <h1 id="Volver_Arriba">core-code-from-scratch-readme</h1>



Indice:
<li><a href="#Semana_1">Semana 1</a></li>
<li><a href="#Semana_2">Semana 2</a></li>
<li><a href="#Semana_3">Semana 3</a></li>

<h1 id="Semana_1"> Semana 1</h1>
<h2> Let's make a PIZZA!:</h2>


<li>Definir el tipo de Pizza: Pizza Italiana, Calzzone o Fugazetta (Seleccion: Fugazzeta)</li>
<li>Definir la receta para comprar los ingredientes de ser necesario
<li>Preparar el espacio de trabajo con todos los implementos a utilizar
<li>Precalentar el horno a 350º
<li>Preparar la masa: En un bol el aceite el agua y la sal, agregar harina, amasar con movimientos envolventes y rápidos, dejar reposar la masa
<li>Separar dos porciones iguales, enharinar la mesa, estirar la primera porción de masa y colocarla en una bandeja de hornear
<li>Agregar una capa abundante de queso y pimentones ahumados cortados en julianas 
<li>Estirar un circula con la segunda porción de masa y colocarlo encima de la capa de queso
<li>Doblar las orillas para cerrar la fugazzeta
<li>Agregar abundantes cebollas cortadas en juliana, queso parmesano y orégano
<li>Perforar la masa con un tenedor para que salga el aire y pintar la masa con aceite de oliva
<li>Hornear a 300º por 15 minutos, dorando sin que se queme
<li>Picarla en porciones triangulares
<li>Disfrutar


<h2>HOT n COLD:</h2>

<h3>Fahrenheit a Celsius</h3>
<li>Establecer la temperatura a convertir</li>
<li>Restar 32</li>
<li>Multiplicar el resultado por 0.5556</li>

<h3>Celsius a Fahrenheit</h3>
<li>Establecer la temperatura a convertir</li>
<li>Multiplicar por 1.8</li>
<li>Sumar 32 al resultado</li>


<h2>GEOMETRY</h2>

<h3>Pyramid</h3>
<li>Definir la longitud de la base</li>
<li>Definir el ancho de la base</li>
<li>Definir la altura de la pirámide</li>
<li>Multiplicar longitud de la base x ancho de la base</li>
<li>Multiplicamos el resultado x la altura de la pirámide</li>
<li>Dividimos el resultado entre 3</li>

<h3>Cube</h3>
<li>Definir el tamaño del lado</li>
<li>Multiplicar el lado x lado x lado</li>

<h3>Sphere</h3>
<li>Definir el diámetro de la esfera</li>
<li>Dividir el diámetro entre dos para determinar el radio</li>
<li>Multiplicar radio x radio x radio para elevar al cubo</li>
<li>Multiplicar el resultado del radio3 x 4</li>
<li>Multiplicar el resultado x Pi (3.14)</li>
<li>Dividir el resultado entre 3</li>

<h2>Find the TREASURES</h2>

<p>Estamos en una habitación con <strong>TRES cofres.</strong>

Sabemos que al menos <strong>UNO</strong> tiene un tesoro en él. 

Cada cofre tiene un mensaje, pero <strong>TODOS los mensajes son MENTIRAS.</strong> 

Caso 1: (Cofre derecho) “Solo uno de estos cofres tiene tesoros”, es una <strong>mentira</strong>, lo que indica que puede haber <strong>más de un tesoro.</strong>

Caso 2: (Cofre medio) “Todos estos cofres tienen tesoros en ellos”, es una <strong>mentira</strong>, lo que indica que hay más de un tesoro, <strong> pero no tres tesoros. </strong>

Descartando que no hay un solo cofre con tesoro y descartando que todos los cofres tienen tesoros, queda como resultado que solo <strong>DOS de los cofres tienen tesoros.</strong>

Caso 3: (Cofre izquierdo) “El cofre del medio tiene un tesoro”, es una <strong>mentira</strong>, lo cual indica que el cofre con tesoro <strong>no está en el medio</strong>

<em>Los DOS tesoros están en el <strong>COFRE DERECHO y el COFRE IZQUIERDO</strong></em></p>

<h2>NUMBERS:</h2>

![Numeros](https://user-images.githubusercontent.com/118138583/229408388-f07a64cb-4066-4dc7-80ac-061a3a982582.png)


<h2>HOW OLD ARE YOU?</h2>
<li>Establecer <strong>año de nacimiento</strong> (1993)</li>
<li>Establecer <strong>año actual</strong> (2023)</li>
<li><strong>Restar</strong> el año de nacimiento, del año actual (2023-1993)</li>

Resultado: <strong>Tengo 30 años</strong>



<h1 id="Semana_2"> Semana 2</h1>
<h2><em>Logic Problem</em></h2>

<p><em>El profesor pregunta a sus 5 alumnos si estudiaron matemáticas ayer.
El maestro sabe que (solo los que estudiaron) estarían diciendo la verdad y los que no, (estarían mintiendo.) 
<strong>Quien esta diciendo la verdad?</strong></em></p>

<li> Alice: "Nadie estudió matemáticas ayer". Si Alice hubiese estudiado, estaria diciendo la verdad, lo que contradice el hecho de que nadie estudio.
<strong>FALSO/ NO ESTUDIO</strong></li>
<li>Eva: "Ayer estudiaron matemáticas 4 personas". Si Eva estaria diciendo la verdad, tendria que haber estudiado junto a Dan , Charlie y Bob, pero si ellos hubiesen estudiado, seria contradictorio a la premisa de que los que estudiaron dice la verdad.
<strong>FALSO/ NO ESTUDIO</strong></li>
<li>Charlie: "2 personas estudiaron matemáticas ayer". Si Charlie estaria diciendo la verdad, tendria que haber estudiado junto a dan o bob, pero sus verdades se contradicen.
<strong>FALSO/ NO ESTUDIO</strong></li>
<li>Dan: "3 personas estudiaron matemáticas ayer".  tomando en cuenta que Alice, Eva, Charlie no estudiaron, esta afirmacion seria falsa
<strong>FALSO/ NO ESTUDIO</strong</li> 

<em>Resultado:</em>
  
 <strong>Bob: "1 persona estudió matemáticas ayer". Bob esta diciendo la verdad, solo el estudió matematicas. </strong></p> 
  
  
  <h2>Which comes first, cereal or milk?</h2>
  
<h3>Pseudocode</h3>
  
  
<li>Definir Cereal Simple o Completo</li>
<h4>Cereal Simple</h4>
<li>Tomar un  bowl</li>
<li>Agregar cereal</li>
<li>Agregar leche</li>
<li>Revolver ingredientes</li>
<h4>Cereal Completo</h4>
<li>Cortar Frutas</li>
<li>Tomar un bowl</li>
<li>Agregar cereal</li>
<li>Agregar fruta picada</li>
<li>Agregar frutos secos/semillas</li>
<li>Agregar miel</li>
<li>Revolver los ingredientes</li>

Fin


<h3>Diagram</h3>

![Diagrama en blanco](https://user-images.githubusercontent.com/118138583/231346895-c4e7a466-2543-41c9-a3a9-fdcb7657425a.png)


<h2>Print My Name</h2>
  
![Captura de pantalla 2023-04-11 205910](https://user-images.githubusercontent.com/118138583/231347018-6ef35bee-98b5-4fc5-a468-d0678b44852f.png)

 <h2>Print my name & age</h2>
  
![Captura de pantalla 2023-04-11 210252](https://user-images.githubusercontent.com/118138583/231347125-d77edccd-2aa8-4441-8eed-c9b29d0af5ac.png)


<h2>Algorithm game</h2>

![Captura de pantalla 2023-04-12 183945](https://user-images.githubusercontent.com/118138583/231609769-a38987fb-e409-40de-a375-753608fc0faf.png)

<h2> Register Form 2</h2>

![Formulario](https://user-images.githubusercontent.com/118138583/232350921-6884fc23-94ba-4318-8bfe-fd38e574596b.png)


<h2>Even and Odd Numbers 2</h2>

![EvenOdd](https://user-images.githubusercontent.com/118138583/232349479-a621d966-96ea-41fc-97cb-6dc025bd70d1.png)

<h2>Truth tables</h2>

<li>T & T = T  ✅</li>
<li>T & F = F  ✅</li>
<li>F & T = T  ✅</li>
<li>F & F = F  ✅</li>
<li>T | T = T ✅</li>
<li>T | F = F ❌</li>
<li>F | T = T ✅</li>
<li>F | F = F ✅</li>
<li>~T = T ❌</li>
<li>~F = T  ✅</li>
<li>(T & F) | (~F) = T ✅  /  F|V </li>
<li>(T | F ) & (F | F) = T ❌ / T & F</li>
<li>~((T | F ) & (F | F)) & F = T ❌ / F&T= F / F&F=F</li>
<li>~((T | F ) & (F | F)) & T = F ✅ / F&T=F = F&T = F   ~T=F / </li>

<h2>Boolean results</h2>

<strong>Algoritmo boolean</strong>

	a <- 5 == 3
	// FALSO 5 no es IGUAL a 3
	b <- 4 <> 3
	// VERDADERO  4 es DIFERENTE a 3
	c <- 7 > 7
	// FALSO 7 es IGUAL a 7, no mayor
	d <- 4 < 4
	// FALSO 4 es IGUAL a 4, no mayor
	e <- 100 <= 90
	// FALSO 100 no es IGUAL o MENOR a 90
	f <- 40 >= 40
	// VERDADERO 40 es IGUAL a 40
  FinAlgoritmo

<h1 id="Semana_3"> Semana 3</h1>

<h2>Simple Calculator</h2>

https://user-images.githubusercontent.com/118138583/233751083-2372e0c0-a40e-4ed3-bcd5-e6d4d6a9256b.mp4

<h2>Special Number</h2>

https://user-images.githubusercontent.com/118138583/233758194-4d4c9a20-d503-4de3-91eb-b2f42a8bb6bc.mp4

		Algoritmo specialNumber
		Escribir 'To know if your number is special or not, type a number here: '
		Leer n
		Si n == 100 Entonces
		Imprimir 'This is a special number'
		FinSi
		Si n < 1000 | n % 10 == 0 Entonces
		Imprimir 'This number is almost special'
		SiNo
		Imprimir 'Just a regular number'
		FinSi
		FinAlgoritmo

<h2>Switch Simple Calculator </h2>

https://user-images.githubusercontent.com/118138583/233808092-f2b43bb4-0206-489f-b05a-9cb59decc32a.mp4

	Algoritmo switchCalculator
	
	Escribir "SWITCH CALCULATOR"
	Escribir 'Ingrese el primer numero'
	Leer entradaUsuario1
	Escribir 'Ingrese el segundo numero'
	Leer entradaUsuario2
	Escribir "Ingrese la operacion a realizar (+,-,*,/)"
	Leer op
	Si op == '+' | op == '-' | op == '*' | op == '/' Entonces
		Escribir 'Procesando: ' + ConvertirATexto(entradaUsuario1)  + op  + ConvertirATexto(entradaUsuario2)
	FinSi
		Segun op Hacer
		"+":
			resultado = entradaUsuario1 + entradaUsuario2
			Imprimir resultado
		"-":
			resultado = entradaUsuario1  - entradaUsuario2
			Imprimir resultado
		"*":
			resultado = entradaUsuario1 * entradaUsuario2
			Imprimir resultado
		"/":
			resultado = entradaUsuario1 / entradaUsuario2
			Imprimir resultado
		De Otro Modo:
			Escribir "La operación no es valida"
				Fin Segun
	FinAlgoritmo
	
	
<h2>MultiOption</h2>

https://user-images.githubusercontent.com/118138583/233818491-dde13082-466a-4790-8808-ca34da8fd8b2.mp4


		Algoritmo multiopcion
	Escribir '=====Multiopcion====='
	Escribir 'Opciones disponibles'
	Escribir '1.Suma de dos numeros'
	Escribir '2.Imprimir dia de la semana'
	Escribir '3.Calcular la longitud de texto'
	Imprimir 'Ingrese la opcion seleccionada'
	Leer entradaUsuario1
	
	Segun entradaUsuario1 Hacer
				"1":
			Imprimir 'Opcion 1: Suma de dos numeros'
			Imprimir 'Ingrese el primer numero'
			Leer entradasuma1
			Imprimir 'Ingrese el segundo numero'
			Leer entradasuma2
			imprimir 'El resultado de la suma es: ' + ConvertirATexto(entradasuma1+entradasuma2)
				"2":
			Imprimir 'Opcion 2: Dia de la semana'
			Imprimir 'Ingrese el dia de la semana en numeros (1-7)'
			Leer entradadias
			Segun entradadias Hacer
				'1':
					Imprimir 'Dia Lunes'
				'2':
					Imprimir 'Dia Martes'
				'3':
					Imprimir 'Dia Miercoles'
				'4':
					Imprimir 'Dia Jueves'
				'5':
					Imprimir 'Dia Viernes'
				'6':
					Imprimir 'Dia Sabado'
				'7':
					Imprimir 'Dia Domingo'
				De Otro Modo: Imprimir 'ERROR EN LA OPERACION, INICIE DE NUEVO'
					
			Fin Segun
				"3":
			Imprimir 'Opcion 3: Calcular longitud de texto'
			Imprimir 'Ingrese el texto: '
			Leer entradatexto
			Imprimir 'Resultado: ' + ConvertirATexto(Longitud(entradatexto))
		De Otro Modo:
			Imprimir 'ERROR EN LA OPERACION, INICIE DE NUEVO'
	Fin Segun
FinAlgoritmo


<h2>Multiplication Tables</h2>

https://user-images.githubusercontent.com/118138583/234171559-57f43902-99c5-4d02-b1de-229f58068eda.mp4

	Algoritmo tablasDeMultiplicar
	Imprimir "------ Tablas de Multiplicar-----"
	Imprimir "Ingrese un numero"
	Leer numero
	Imprimir "#Calculando tabla del " + ConvertirATexto(numero) + " # "
	Definir iterador Como Entero
	iterador = 1
	Mientras iterador <= 10 Hacer
		Imprimir  ConvertirATexto(numero) + " * " + ConvertirATexto(iterador) " = " ConvertirATexto(numero * iterador)
		iterador= iterador + 1
	Fin Mientras
	FinAlgoritmo

<h2>Simple calculator with Do While</h2>



https://user-images.githubusercontent.com/118138583/235806498-152888b8-45b8-421d-b182-cb7098d933dd.mp4


		Algoritmo SimpleCalculatorDW
	Repetir
		Escribir "SIMPLE CALCULATOR"
		Escribir 'Ingrese el primer numero'
		Leer entradaUsuario1
		Escribir 'Ingrese el segundo numero'
		Leer entradaUsuario2
		Escribir "Ingrese la operacion a realizar (+,-,*,/)"
		Leer op
		Si op == '+' | op == '-' | op == '*' | op == '/' Entonces
			Si op== '+' Entonces
				imprimir 'Resultado: ' + ConvertirATexto(entradaUsuario1+entradaUsuario2)
			SiNo
				Si op== '-' Entonces
					Imprimir 'Resultado: ' + ConvertirATexto(entradaUsuario1-entradaUsuario2)
				Sino
					Si op== '*' Entonces
						imprimir 'Resultado: ' + ConvertirATexto(entradaUsuario1*entradaUsuario2)
					SiNo
						si op== '/' Entonces
							imprimir 'Resultado ' + ConvertirATexto(entradaUsuario1/entradaUsuario2)
							
						FinSi
					FinSi
				FinSi
			FinSi
		SiNo
			Imprimir 'ERROR, OPERACION INCORRECTA'
		FinSi
		Escribir "Deseas realizar otra operacion?"
		Leer continuacion
	Hasta Que continuacion == 'no'
	FinAlgoritmo

<h2>Multiplication Tables with For</h2>



https://user-images.githubusercontent.com/118138583/235820846-d07c43e1-683b-4e10-aea4-28302d83d979.mp4


		Algoritmo tablasDeMultiplicar
	Imprimir "------ Tablas de Multiplicar-----"
	Imprimir "Ingrese un numero"
	Leer numero
	Imprimir "#Calculando tabla del " + ConvertirATexto(numero) + " # "
	Para i <- 1 Hasta 10 Con Paso 1 Hacer
		Imprimir  ConvertirATexto(numero) + " * " + ConvertirATexto(i) " = " ConvertirATexto(numero * i)
	Fin Para
	
	FinAlgoritmo





<h6><i><a href="#Volver_Arriba"> Volver al indice ↑ </a></li><h6>

