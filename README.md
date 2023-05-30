<h1 align="center">core-code-from-scratch-readme</h1>

# Algorithms - Week 1
## Week challenges (Wednesday)
### 1. Pizza algorithm
**Ingredients**
- pizza dough
- Tomato sauce
- Mozzarella cheese
- Pepperoni

**Steps**
1. Light the oven.
2. Do the shape of the pizza.
3. Spreed the tomato sauce over the pizza dough
4. Sprinkle mozzarella cheese over the pizza dough.
5. Add pepperoni for our pizza.
6. Get our pizza inside the oven.
7. Bake for at least 15 minutes.
8. Take our pizza out of the oven.


### 2. Hot N Cold 🤒 🧊 🔥
**Steps**
1. Ask the user if he wants to convert Celsius or Fahrenheit and respective temperature.
2. If the user selects celsius, then use the next formula to convert to fahrenheit: F = (C*9/5).<br>
    2.1. Show the final temperature in F units.
3. If the user selects Fahrenheit, then convert it to celsius by using the next formula: C = (F-32)*5/9.<br>
    3.1. Show the final temperature in C units.

### 3. Geometry 📐

1. Ask the user the shape he wants to calculate the volume.
2. If the shape is "pyramid", do<br>
2.1 Ask for the length, width, and height of the pyramid.<br>
2.2 Use and replace values in the next formula: V = (length * width * height) / 3.<br>
2.3 Show the volume of the pyramid.
3. If the shape is "cube", do <br>
3.1 Ask for the length.<br>
3.2 Use and replace values in the next formula: V = length * length * length.<br>
3.3 Show the volume of cube.
4. If the shape is "sphere", do<br>
4.1 Ask the user for the radius.<br>
4.2 Use and replace in the next formula: V = (4/3) * pi * r^3.<br>
4.3 Show the volume of the sphere

## Week challenges (Thursday)
### 1. Numbers 📊
1. Ask the user to enter a number.
2. Check if the number es divided by 2.
3. If the number is divided by 2, then show in console "Number is even".
4. If not, then show the next message "Number is odd"

![2023-04-02_22-57](https://user-images.githubusercontent.com/72572887/229415225-ae48864b-1c57-479d-9307-324ac5bf1333.png)


### 2. Date of birth 👧
1. Ask the user to enter their date of birth with the next way DD-MM-YYYY.
2. Separate by day, month, and year.
3. Start to calculate the current date.
4. Substract the user's birth year from the current year.
5. Show the person's age.

### 3. Treasures 👑
Chest A -> This chest has a treasure -> false.<br>
Chest B -> All the chests have treasures -> true.<br>
Chest C -> Just one of these chests has a treasure -> false.

Answer: chest A and chest C have the treasure.

# Pseudocode - Week 2
## Week challenges (Monday)
### 1. Logic problem
1. If Alice is telling the truth, then nobody studied math.
2. If bob is telling the truth, it means that just one person studied math yesterday.
3. If Charlie is saying the truth, then exactly two people studied math yesterday.
4. If Dan is telling the truth, then exactly three people studied math yesterday.
5. If Eva is telling the truth, then exactly for people studied math yesterday.

Therefore, only Bob is telling the truth and just one person studied math yesterday.

### 2. Cereal vrs Milk
1. Get a bowl.
2. Pour the milk into the bowl.
3. Add some sugar.
4. Pour cereal into the bowl.
5. Enjoy.

![image](https://user-images.githubusercontent.com/72572887/232366819-86436772-41c6-4ee6-8edb-8a0d2d3cebd0.png)

## Week challenges (Tuesday)
### 1. Install PSeInt
![image](https://user-images.githubusercontent.com/72572887/232367553-518fc3d3-da33-4dde-bdc5-f856620b7844.png)
### 2. Print my name
```python
Algoritmo print_my_name
	Escribir 'Printing my name: Héctor'
FinAlgoritmo
```
![image](https://user-images.githubusercontent.com/72572887/232368009-356f5647-91a1-4c8d-891e-1f7411440321.png)
### 3. Print my name & age
```python
Algoritmo print_my_name
	Escribir 'Printing my name: Héctor'
	Escribir 'Age: 23'
FinAlgoritmo
```
![image](https://user-images.githubusercontent.com/72572887/232368852-cf29ffaa-b9f7-4987-bd1d-cca6f1342e44.png)

## Week challenges (Wednesday)
### 1. Algorithm game
![image](https://user-images.githubusercontent.com/72572887/232374332-e09831bb-5f00-4bc8-816c-f86e8bdb3aba.png)

### 2. Mod
```python
Algoritmo EvenOrOdd
	Escribir "Write a number: "
	Leer number
	Si number mod 2 = 0 Entonces
		Escribir "0"
	SiNo
		Escribir "1"
	FinSi
FinAlgoritmo
```
![image](https://user-images.githubusercontent.com/72572887/232374809-51fe36cf-f1f2-44e1-a927-91d246e51d2f.png)

### 3. Register form
```python
Algoritmo RegistrationForm
    Escribir "What is your first name?"
    Leer firstName
	
    Escribir "What is your last name?"
    Leer lastName
	
    Escribir "How old are you?"
    Leer age
	
    Escribir "What is your email address?"
    Leer email
	
    Escribir "What is your address?"
    Leer address

    Escribir '--------------------------'
    Escribir "First Name: " + firstName
    Escribir "Last Name: " + lastName
    Escribir "Age: " + age
    Escribir "Email: " + email
    Escribir "Address: " + address
	Escribir '--------------------------'
FinAlgoritmo

```

![image](https://user-images.githubusercontent.com/72572887/232375626-ade81c7f-d976-466a-9118-b8f1cc88d34c.png)


## Week challenges (Thursday)
### 1. Truth tables
1. T & T = T -> ✅
2. T & F = F ->✅
3. F & T = T ->❌
4. F & F = F ->✅
5. T | T = T ->✅
6. T | F = F ->❌
7. F | T = T ->✅
8. F | F = F ->✅
9. ~T = T ->❌
10. ~F = T ->✅
11. (T & F) | (~F) = T ->✅
12. (T | F ) & (F | F) = T ->❌
13. ~((T | F ) & (F | F)) & F = T ->✅
14. ~((T | F ) & (F | F)) & T = F ->✅

### 2. Boolean results
```python
Algoritmo boolean
	// The following line assigns the result of the comparison 5 equals 3 to variable a
	a <- 5 == 3 // a = False

	// The following line assigns the result of the comparison 4 not equals 3 to variable b
	b <- 4 <> 3 // b = True

	// The following line assigns the result of the comparison 7 greater than 7 to variable c
	c <- 7 > 7 // c = False

	// The following line assigns the result of the comparison 4 less than 4 to variable d
	d <- 4 < 4 // d = False

	// The following line assigns the result of the comparison 100 less than or equal to 90 to variable e
	e <- 100 <= 90 // e = False

	// The following line assigns the result of the comparison 40 greater than or equal to 40 to variable f
	f <- 40 >= 40 // f = True
FinAlgoritmo

```

### 3. Identify odd and even numbers
```python
Algoritmo EvenOrOdd
	Escribir "Write a number: "
	Leer number
	Si number mod 2 = 0 Entonces
		Escribir "Number "+ConvertirATexto(number) +" is even"
	SiNo
		Escribir "Number "+ConvertirATexto(number) +" is odd"
	FinSi
FinAlgoritmo
```
![image](https://user-images.githubusercontent.com/72572887/232377498-ba783a49-303b-42ac-9e7d-87861f493aba.png)


# Pseudocode - Week 3
## Week challenges (Monday)
### 1. Simple calculator
```python
Algoritmo calc

Escribir "Ingrese el primer número:"
Leer num1

Escribir "Ingrese el segundo número:"
Leer num2

Escribir "Ingrese el signo de la operacion que desea realizar:"
Leer operacion

Si operacion = "+" Entonces
    resultado = num1 + num2
    operacion_texto = "sumar"
Sino Si operacion = "-" Entonces
    resultado = num1 - num2
    operacion_texto = "restar"
Sino Si operacion = "*" Entonces
    resultado = num1 * num2
    operacion_texto = "multiplicar"
Sino Si operacion = "/" Entonces
    Si num2 = 0 Entonces
        Escribir "Division invalida"
        FinAlgoritmo
    FinSi
    resultado = num1 / num2
    operacion_texto = "dividir"
Sino
    Escribir "La operación ingresada no es válida"
    FinAlgoritmo
FinSi

Escribir "Procesando: " + num1 + " " + operacion_texto + " " + num2
Escribir "Resultado: " + resultado

FinAlgoritmo
```

### 2. Special number
```python
Algoritmo specialNumber
	Leer n
	Si n == 100 Entonces
		Imprimir 'This is a special number'
	SiNo
		Si (n < 1000) & (n % 10 == 0) Entonces
			Imprimir  'This number is almost special'
		SiNo
			Imprimir 'Just a regular number'
		FinSi
	FinSi
FinAlgoritmo
```
## Week challenges (Tuesday)
### 1. Simple calculator with Switch 
```python
Proceso switch_app

Definir num1, num2, resultado Como Real
Definir operacion Como Caracter

Escribir "Ingrese el primer número: "
Leer num1

Escribir "Ingrese el segundo número: "
Leer num2

Escribir "Ingrese la operación a realizar: "
Leer operacion

Segun operacion Hacer
    "+":
        resultado <- num1 + num2
        Escribir "Procesando: ", num1, " + ", num2
        Escribir "Resultado: ", resultado
    "-":
        resultado <- num1 - num2
        Escribir "Procesando: ", num1, " - ", num2
        Escribir "Resultado: ", resultado
    "*":
        resultado <- num1 * num2
        Escribir "Procesando: ", num1, " * ", num2
        Escribir "Resultado: ", resultado
    "/":
        Si num2 = 0 Entonces
            Escribir "Error: División por cero"
        Sino
            resultado <- num1 / num2
            Escribir "Procesando: ", num1, " / ", num2
            Escribir "Resultado: ", resultado
        FinSi
    De Otro Modo:
        Escribir " Error: Operación no válida"
FinSegun

FinProceso

```

### 2. Multi Option Program
```python
Proceso opc
	Definir opcion Como Entero
	Escribir "Seleccione una opción:"
	Escribir "1. Sumar"
	Escribir "2. Imprimir día de la semana según número"
	Escribir "3. Calcular longitud de un texto"
	Leer opcion

	Segun opcion Hacer
		1:
			Definir num1, num2, resultado Como Entero
			Escribir "Ingrese el primer número:"
			Leer num1
			Escribir "Ingrese el segundo número:"
			Leer num2
			resultado <- num1 + num2
			Escribir "El resultado de la suma es:", resultado
		2:
			Definir dia Como Entero
			Escribir "Ingrese el número del día de la semana:"
			Leer dia
			Segun dia Hacer
				1: Escribir "Lunes"
				2: Escribir "Martes"
				3: Escribir "Miércoles"
				4: Escribir "Jueves"
				5: Escribir "Viernes"
				6: Escribir "Sábado"
				7: Escribir "Domingo"
				Sino: Escribir "El número de día invalido"
			FinSegun
		3:
			Definir texto Como Cadena
			Escribir "Ingrese un texto:"
			Leer texto
			Escribir "La longitud del texto es:", Longitud(texto)
		Sino:
			Escribir "La opción ingresada no es válida"
	FinSegun
FinProceso


```

## Week challenges (Wednesday)
### 1. Multiplication Tables
```python
Proceso MultiplicationTables
	Definir num, i Como Entero
	
	Escribir "Ingrese un número para imprimir su tabla de multiplicar: "
	Leer num
	
	i = 1
	Mientras i <= 10 Hacer
		Escribir num, " x ", i, " = ", num*i
		i = i + 1
	Fin Mientras
FinProceso

```

### 2. Simple Calculator with Do While
```python
Proceso Calculadora_do_while
	Definir opcion Como Caracter
	Definir num1, num2, resultado Como Entero
	Definir continuar Como Logico
	continuar = Verdadero
	
	Repetir
		Escribir "Ingrese el primer número: "
		Leer num1
		Escribir "Ingrese el segundo número: "
		Leer num2
		
		Escribir "Seleccione una operación: "		
		Leer opcion
		
		Segun opcion Hacer
			"+" :
				resultado = num1 + num2
				Escribir "Resultado: ", resultado
			"-" :
				resultado = num1 - num2
				Escribir "Resultado: ", resultado
			"*" :
				resultado = num1 * num2
				Escribir "Resultado: ", resultado
			"/" :
				resultado = num1 / num2
				Escribir "Resultado: ", resultado
			De Otro Modo :
				Escribir "Opción no válida"
		FinSegun
		
		Escribir "¿Desea realizar otra operación? (s/n): "
		Leer opcion
		
		Si opcion = "s" Entonces
			continuar = Verdadero
		Sino
			continuar = Falso
		FinSi
	Hasta Que continuar = Falso
FinProceso

```

## Week challenges (Thursday) 
### 1. Multiplication Tables with For
```python
Proceso mult_for
    Definir num, i, result Como Entero
    
    Escribir "Ingrese un número:"
    Leer num
    
    Para i = 1 Hasta 10 Con Paso 1 Hacer
        result = num * i
        Escribir num, " x ", i, " = ", result
    FinPara
    
FinProceso
```

### 2. Ascending and Descending Numbers
```python
Algoritmo PrintNumbersAscDesc
    Escribir "Ingrese un número:"
    Leer numero
    
    Escribir "Orden ascendente (A) || Orden descendente (D)?"
    Leer opcion
    
    Si opcion = "A" entonces
        Para i desde 0 hasta numero hacer
            Escribir i
        FinPara
    Sino Si opcion = "D" entonces
        Para i desde numero hasta 0 hacer
            Escribir i
        FinPara
    Sino
        Escribir "La opción ingresada no es válida"
    FinSi
FinAlgoritmo
```

### 3. Greetings
```python
Algoritmo Greetings
	Imprimir '======= Greetings ======='
	Definir continuar Como Cadena
	Definir cantidadSaludos Como Entero
	cantidadSaludos <- 0
	continuar <- 'Si'
	Mientras continuar == 'Si' Hacer
		Imprimir 'Ingrese la hora actual (0-23):'
		Leer hora
		Si hora <= 12 Entonces
			Imprimir 'Buenas dias!'
		SiNo
			Si hora <= 18 Entonces
				Imprimir 'Buenas tardes!'
			SiNo
				Imprimir 'Buenas noches!'
			Fin Si
		Fin Si

		cantidadSaludos <- cantidadSaludos + 1

		Imprimir 'Desea continuar ? Si/No'
		Leer continuar
	Fin Mientras

	Imprimir 'Cantidad de Saludos realizados: ' + ConvertirATexto(cantidadSaludos)
FinAlgoritmo
```
# Pseudocode - Week 4
## Week challenges (Monday)
### 1. Average sales and commission
```python
Algoritmo Commission
    Dim num_sales, i Como Entero
    Dim sale, total_sales, avg_sale, commission Como Real
    
    Escribir "How many sales did the seller make?"
    Leer num_sales
    total_sales <- 0
    
    Para i <- 1 Hasta num_sales Con Paso 1 Hacer
        Escribir "Enter the value of sale:"
        Leer sale
        total_sales <- total_sales + sale
    FinPara
    
    avg_sale <- total_sales / num_sales
    
    Si num_sales > 5 Entonces
        commission <- total_sales * 0.15
    Sino
        commission <- total_sales * 0.10
    FinSi
    
    Escribir "The average value of each sale is $", avg_sale, "."
    Escribir "The seller's commission is $", commission, "."
FinAlgoritmo
```
### 2. Even or odd
```python
Algoritmo MostrarNumerosParesImpares
    Definir num, i como Entero
    num <- 0
    Mientras num < 1 o num > 50 hacer
        Escribir "Ingrese un número entre 1 y 50:"
        Leer num
        Si num < 1 o num > 50 entonces
            Escribir "Error: el número debe estar entre 1 y 50"
        FinSi
    FinMientras
    
    Escribir "Los números del 1 al", num, "son:"
    Para i desde 1 hasta num hacer
        Si num % 2 = 0 entonces
            Si i % 2 = 0 entonces
                Escribir i
            FinSi
        Sino
            Si i % 2 <> 0 entonces
                Escribir i
            FinSi
        FinSi
    FinPara
    
FinAlgoritmo
```
## Week challenges (Tuesday)
### 1. Predefined functions
```
  - Predefined functions
    - Maths
        - abs
        - trunc
        - redon
        - azar
    - Chain
        - longitud
        - mayusculas
        - minusculas
        - subcadena
```

### 2. Full Name
```python
Algoritmo CapitalizeName    
    Escribir "Enter your first name:"
    Leer nombre1
    
    Escribir "Enter your last name:"
    Leer nombre2
    
	Definir  primer_caracter Como Caracter
	primer_nombre = Mayusculas(subcadena(nombre1,0,1));
	resto_primer_nombre = Minusculas(Subcadena(nombre1, 2, Longitud(nombre1)))
	
	Total_primer_nombre = primer_nombre + resto_primer_nombre
	//--------------------------------------------------------------------------
	primer_apellido = Mayusculas(subcadena(nombre2,0,1));
	resto_primer_apellido = Minusculas(Subcadena(nombre2, 2, Longitud(nombre2)))
	
	Total_primer_apellido = primer_apellido + resto_primer_apellido
	
    nombre_completo = nombre1_capitalizado + " " + nombre2_capitalizado
    Escribir "Your capitalized name is:", Total_primer_nombre + " " +Total_primer_apellido
FinAlgoritmo
```
### 3. Throw dice
```python
Algoritmo RollDice
    Para i = 1 Hasta 10 Hacer
        dado1 = Aleatorio(1,6)
        dado2 = Aleatorio(1,6)
        
        Si dado1 = dado2 Entonces
			Imprimir  dado1," ", dado2 ," the dice are the same"
		SiNo
			Imprimir  dado1," ", dado2
        FinSi  
    FinPara
FinAlgoritmo
```
## Week challenges (Wednesday)
### 1. Distance to zero
```python
Algoritmo FurthestFromZero

    max_valor = 0

    Para i = 1 Hasta 5 Hacer
        Escribir "Enter value ", i, ":"
        Leer valor

        Si Abs(valor) > Abs(max_valor) Entonces
            max_valor = valor
        FinSi
    FinPara
    Escribir "The furthest value from zero is:", trunc(max_valor)
    
FinAlgoritmo
```
### 2. Toss coin

```python
Algoritmo tossCoin
    Escribir "Enter the name of the first player"
    Leer player1
    Escribir "Enter the amount to play"
    Leer amount1
    Escribir "Enter the name of the second player"
    Leer player2
    Escribir "Enter the amount to play"
    Leer amount2
    
    Si amount1 <= 0 O amount2 <= 0 Entonces
        Si amount1 <= 0 Y amount2 <= 0 Entonces
            Escribir "Game canceled"
        Sino
            Si amount1 <= 0 Entonces
                Escribir "Player wins: ", player2, " Amount won: 0"
            Sino
                Escribir "Player wins: ",player1, " Amount won: 0"
            FinSi
        FinSi
    SiNo
        Definir ganador como Cadena
        Definir valorGanador como Entero
		
        Definir resultadoAleatorio como Entero
        resultadoAleatorio = Aleatorio(1, 2)
		
        Si resultadoAleatorio = 1 Entonces
            ganador = player1
            valorGanador = amount2
        SiNo
            ganador = player2
            valorGanador = amount1
        FinSi
		
        Escribir "Player wins: ", ganador, " Amount won: ", valorGanador
    FinSi
FinAlgoritmo
```

## Week challenges (Thursday)
### 2. Total price
```python
Funcion value <-TotalPrice (price, iva)
	Definir value Como Real
Si price < 3000 Entonces
	value = ( price + (price/100*iva) )
SiNo
	value = ( price + (price/100*iva) ) / 100*90
FinSi

FinFuncion
	
Proceso Print
	Imprimir TotalPrice(3589,15)
FinProceso	
```
### 3. Reverse direction and size
```python
Funcion result <- ReverseDirectionAndSize (string)
	Definir result Como Caracter;
	result = "";
	Para count = Longitud(string) Hasta 0 Con Paso -1 Hacer
		letter = Subcadena(string,count,count);
		SI letter = Mayusculas(letter) Entonces
			letter = Minusculas(letter)
		SiNo
			letter = Mayusculas(letter)
		FinSi
		result = Concatenar(result, letter)
	FinPara
Fin Funcion

Algoritmo example_ReverseDirectionAndSize
	Imprimir ReverseDirectionAndSize("Comida")
FinAlgoritmo
```
# Pseudocode & Javascript - Week 5
## Week challenges (Monday)
### 1. Time Converter
```python
Funcion result <- timeConverter (number)
	Definir result Como Caracter;
	Definir days, hours, minutes, seconds Como Entero;
	seconds = number % 60;
	minutes = Trunc(number/60) % 60;
	hours = Trunc(number/3600) % 24;
	days = Trunc(number/86400);
	
	result = "days: "+ ConvertirATexto(days) + ", hours: "+ConvertirATexto(hours) + ", minutes: "+ ConvertirATexto(minutes) + ", seconds: "+ ConvertirATexto(minutes)+", seconds: "+ConvertirATexto(seconds);
Fin Funcion

Algoritmo exampleTimeConverter
	Imprimir timeConverter(9000)
FinAlgoritmo
```
### 2. Mid point
```python
Funcion result <- midpoint (numero1, numero2)
	Definir puntoMedio Como Real
    result <- (numero1 + numero2) / 2
FinFuncion

Proceso hola
	Definir numero1, numero2, resultado Como Real
	numero1 <- 25
	numero2 <- 10
	resultado <- midpoint(numero1, numero2)
	Escribir("Punto medio: " + ConvertirATexto(resultado))	
FinProceso
```

## Week challenges (Wednesday) 
### 1. Cashier
```python
Funcion balance <- cashier ()
	Definir balance Como Real;
	balance = 1000;
	Repetir
		Imprimir "select an option:";
		Imprimir "a. to deposit.";
		Imprimir "b. withdraw.";
		Imprimir "c. go out.";
		leer option
		Si option = 'a' Entonces
			balance = balance + deposit()
		FinSi
		Si option = 'b' Entonces
			balance = balance - withdraw()
		FinSi
	Mientras Que option = "a" | option = "b"
Fin Funcion

Funcion value <- deposit()
	Imprimir "how much do you want to deposit:";
	leer value
FinFuncion

Funcion value <- withdraw()
	Imprimir "how much do you want to withdraw:";
	leer value
FinFuncion

Algoritmo exampleCashier
	Imprimir cashier()
FinAlgoritmo
```
### 2. Weather average
```python
Funcion celsius <- fahrenheitToCelsius (fahrenheit)
	Definir celsius Como Real;
	celsius = (fahrenheit - 32 ) / 1.8
Fin Funcion

Algoritmo exampleWeatherAverage
	count = 0;
	total = 0;
	Repetir
		Imprimir "select an option:";
		Imprimir "a. enter degrees celsius.";
		Imprimir "b. enter degrees fahrenheit.";
		Imprimir "x. go out.";
		leer option
		Si option = "a" | option = "b" Entonces
			leer degree
			count = count + 1;
		FinSi
		Si option = 'a' Entonces
			total = total + degree;
		FinSi
		Si option = 'b' Entonces
			total = total + fahrenheitToCelsius(degree);
		FinSi
	Mientras Que option = "a" | option = "b"
	Imprimir total / count;
FinAlgoritmo
```
## Week challenges (Thursday) 
### 1. If
```js
if (vari == 1) {
    console.log('var is number 1');
}else{
    console.log('var is not 1')
}
```
### 2. While
```js
while (vari < 10) {
    console.log(vari)
    vari++;
}
```
### 3. For
```js
for (let i = 0; i < 10; i++) {
    console.log(i)
}
```

# JavaScript - Week 6
## Week challenges (Tuesday)
### 2. Variables
```js
let firstname = 'Lata';
```
### 3. What is x?
```
// The value will be: 'Geeta'
```
### 4. Several variables
```js
let flower = 'rose';
let tree = 'maple';
```
### 5. Reassignment
```js
let x = 'Tic';
x = 'Tac';
x = 'Toe';
//x has the value 'Toe'.
```
### 6. Assign variables
```js
let x = 'Laurel';
let y = 'Hardy';
let z = y;
y = x;
x = z;

//x has the value 'Hardy'.
```
## Week challenges (Wednesday)
### 2. Functions
```js
function hello(){
  return 'Hello world!';
}
```
### 3. Multiple functions

```js
function a(){
  return 'Hello a!';
}

function b(){
  return 'Hello b!';
}
```
### 4. Function calls
```js
function greet(){
  return 'Haydo!';
}

let salutation = greet();
```
### 5. What is x? (function version)
```js
function reply(phrase) {
  return phrase;
}

let x = reply('How do you do?');
//x has the value 'How do you do?'.
```
### 6. Parameters
```js
function echo(text){
     return text;
}
```
## Week challenges (Thursday)
### 1. Strings
```js
function greet(text){
    return `Hello ${text}!`
}
```
