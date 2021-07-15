1) Escribir un programa que pida al usuario una palabra y la muestre por pantalla 10 veces.

palabra = input("Ingrese una palabra: ")
cantidad = 10
x = 0

while cantidad > x:
    print (palabra)
    x += 1

---------------------------------------------------------------------------------------------

2) Escribir un programa que pregunte al usuario su edad y muestre por pantalla todos los años
que ha cumplido (desde 1 hasta su edad).

edad = int(input("¿Cuantos anios tiene?: "))

for numero in range(edad):
    print(f"{numero+1}")

---------------------------------------------------------------------------------------------
3) Escribir un programa que pida al usuario un número entero positivo y muestre por pantalla
todos los números impares desde 1 hasta ese número separados por comas.

entero = int(input("Ingrese un numero entero positivo: "))

for numero in range(1, entero + 1):
    if numero % 2 != 0:
        print(numero, end=", ")

---------------------------------------------------------------------------------------------
4) Escribir un programa que pida al usuario un número entero positivo y muestre por pantalla
la cuenta atrás desde ese número hasta cero separados por comas.

entero = int(input("Ingrese un numero entero positivo: "))

for numero in range(1,entero+1):
    print(entero-numero+1)

---------------------------------------------------------------------------------------------
5) Escribir un programa que pregunte al usuario una cantidad a invertir, el interés anual y el
número de años, y muestre por pantalla el capital obtenido en la inversión cada año que dura
la inversión.

---------------------------------------------------------------------------------------------
6) Escribir un programa que pida al usuario un número entero y muestre por pantalla un
triángulo rectángulo como el de más abajo (para n=5), de altura el número introducido.
*
**
***
****
*****

x = 1

while x <= 5:
    print ("#" * x)
    x = x + 1

print ("Fin.")

---------------------------------------------------------------------------------------------
7) Escribir un programa que pida un número entero y muestra la tabla de multiplicar de ese
número, ej: (n = 6)
1x6 = 6
2x6 = 12
3x6 = 18
….
10x6 = 60

---------------------------------------------------------------------------------------------
8) Escribir un programa que pida al usuario un número entero y muestre por pantalla un
triángulo rectángulo como el de más abajo.
1
3 1
5 3 1
7 5 3 1
9 7 5 3 1

producto = 2
for numero in range (1,10 +1):
    print (f"{producto} x {numero} = {producto * numero}")
    producto *= numero

  VER!! VER!! VER!!

---------------------------------------------------------------------------------------------
9) Escribir un programa que almacene la cadena de caracteres contraseña en una variable,
pregunte al usuario por la contraseña hasta que introduzca la contraseña correcta.

---------------------------------------------------------------------------------------------
10) Escribir un programa que pida al usuario un número entero y muestre por pantalla si es un
número primo o no.

---------------------------------------------------------------------------------------------
11) Escribir un programa que pida al usuario una palabra y luego muestre por pantalla una a
una las letras de la palabra introducida empezando por la última.

---------------------------------------------------------------------------------------------
12) Escribir un programa en el que se pregunte al usuario por una frase y una letra, y muestre
por pantalla el número de veces que aparece la letra en la frase.

---------------------------------------------------------------------------------------------
13) Escribir un programa que muestre el eco de todo lo que el usuario introduzca hasta que 
el usuario escriba “salir” que terminará.
