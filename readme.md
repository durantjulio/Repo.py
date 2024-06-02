intro python
importar: print("hola mundo")

int:numero, str:letras float:numeros con decimales

se puede poner escribir variables en una linea:
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)

Y puede asignar el mismo valor a varias variables en una línea:
x = y = z = "Orange"
print(x) #orange
print(y) #orange
print(z) #orange

Si tiene una colección de valores en una lista, tupla, etc. Python le permite extraer los valores en variables. A esto se le llama desempaquetar.

Descomprimir una lista:
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)

La función Python se utiliza a menudo para generar variables.print()
Ejemplo
x = "Python es lo mejor"
print(x) #Python es lo mejor

En la función, se generan varios variables, separadas por una coma:print()

x = "Python"
y = "es"
z = "lo mejor"
print(x, y, z) #Python es lo mejor

def se utiliza para definir una funcion 
Las variables globales pueden ser utilizadas por todo el mundo, tanto dentro de funciones y exteriores.

Cree una variable fuera de una función y utilícela dentro de la función:

x = "increible"

def myfunc():
  print("Python es " + x) #Python es increible

myfunc()
