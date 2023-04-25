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
