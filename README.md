Listo ✅
Ya te armé el Markdown completo y ordenado en el canvas, listo para:

📄 estudiar

📤 compartir

🖨️ imprimir

🧠 usar como chuleta rápida

Si querés, en el próximo paso puedo:

adaptarlo a nivel principiante total

convertirlo en PDF

agregar ejercicios con solución

o hacer una versión aún más resumida (1 hoja)

agregame listas   metodos de cadenas  y metodos de numeros 
Guía Rápida De Python – Fundamentos
📚 GUÍA RÁPIDA DE PYTHON – FUNDAMENTOS
1️⃣ print() – MOSTRAR INFORMACIÓN
# Imprimir texto simple
print("Hola Mundo")


# Imprimir variables
nombre = "Juan"
edad = 25
print("Nombre:", nombre, "Edad:", edad)


# Imprimir con formato f-string
print(f"Nombre: {nombre}, Edad: {edad}")


# Imprimir en múltiples líneas
print("Línea 1\nLínea 2\nLínea 3")
2️⃣ input() – LEER DATOS DEL USUARIO
# Leer texto simple
nombre = input("¿Cuál es tu nombre? ")
print(f"Hola, {nombre}")


# Leer número y convertir
edad = int(input("¿Cuántos años tienes? "))
print(f"El año que viene tendrás {edad + 1} años")


# Leer múltiples valores
valores = input("Ingresa dos números separados por espacio: ")
num1, num2 = map(int, valores.split())
3️⃣ PARSEO – CONVERTIR TIPOS DE DATOS
# String a Entero
texto_numero = "123"
numero = int(texto_numero)


# String a Decimal
texto_decimal = "45.67"
decimal = float(texto_decimal)


# Número a String
edad = 25
texto_edad = str(edad)


# String a Lista
frase = "hola mundo"
lista_palabras = frase.split()
4️⃣ while – BUCLE CONDICIONAL
# Contador básico
contador = 1
while contador <= 5:
    print(f"Contador: {contador}")
    contador += 1


# Validación de entrada
respuesta = ""
while respuesta != "salir":
    respuesta = input("Escribe 'salir' para terminar: ")
    print(f"Escribiste: {respuesta}")


# Menú interactivo
opcion = 0
while opcion != 3:
    print("\n1. Saludar")
    print("2. Despedir")
    print("3. Salir")
    opcion = int(input("Selecciona opción: "))
    
    if opcion == 1:
        print("¡Hola!")
    elif opcion == 2:
        print("¡Adiós!")
5️⃣ for – BUCLE CON ITERACIÓN
# Recorrer lista
frutas = ["manzana", "banana", "naranja"]
for fruta in frutas:
    print(f"Fruta: {fruta}")


# Recorrer con range
for i in range(5):
    print(f"Número: {i}")


for i in range(1, 6):
    print(f"Número: {i}")


# Recorrer string
palabra = "Python"
for letra in palabra:
    print(f"Letra: {letra}")


# Recorrer con índice
for indice, fruta in enumerate(frutas):
    print(f"Índice {indice}: {fruta}")
6️⃣ LISTAS – ARRAYS EN PYTHON
# Crear listas
numeros = [1, 2, 3, 4, 5]
nombres = ["Ana", "Juan", "María"]
mezclada = [1, "texto", True, 3.14]


# Acceder elementos
print(numeros[0])
print(numeros[-1])


# Modificar listas
numeros.append(6)
numeros.insert(2, 99)
numeros.remove(3)


# Slicing
print(numeros[1:4])
print(numeros[:3])
print(numeros[3:])


# Operaciones
lista1 = [1, 2, 3]
lista2 = [4, 5, 6]
combinada = lista1 + lista2
repetida = lista1 * 3


# Métodos
lista = [3, 1, 4, 1, 5, 9]
lista.sort()
lista.reverse()
cantidad = len(lista)
7️⃣ TIPOS DE DATOS BÁSICOS
# int
edad = 25


# float
precio = 19.99


# str
nombre = "Juan"


# bool
es_mayor = True


# list
frutas = ["manzana", "banana"]


# tuple
coordenadas = (10, 20)


# dict
persona = {
    "nombre": "Ana",
    "edad": 30,
    "ciudad": "Madrid"
}


# set
unicos = {1, 2, 3, 3, 2}
8️⃣ EJEMPLOS PRÁCTICOS COMBINADOS
# Sistema de notas
notas = []
while True:
    nota = input("Ingresa una nota (o 'fin' para terminar): ")
    if nota.lower() == 'fin':
        break
    notas.append(float(nota))


print(f"\nTotal de notas: {len(notas)}")
print(f"Promedio: {sum(notas)/len(notas):.2f}")


# Buscar en lista
productos = ["leche", "pan", "huevos", "azúcar"]
busqueda = input("\n¿Qué producto buscas? ")
if busqueda in productos:
    print(f"{busqueda} está en la lista")
else:
    print(f"{busqueda} NO está en la lista")


# Contador de palabras
frase = input("\nIngresa una frase: ")
palabras = frase.split()
print(f"Tu frase tiene {len(palabras)} palabras")
9️⃣ MÉTODOS DE LISTAS
numeros = [1, 2, 3]


numeros.append(4)      # Agrega al final
numeros.extend([5, 6]) # Agrega varios
numeros.insert(1, 99)  # Inserta en índice
numeros.remove(99)     # Elimina por valor
numeros.pop()          # Elimina último
numeros.clear()        # Vacía la lista


numeros.sort()         # Ordena
numeros.reverse()      # Invierte


print(len(numeros))    # Cantidad de elementos
🔟 MÉTODOS DE CADENAS (STR)
texto = " Hola Mundo Python "


texto.lower()        # minusculas
texto.upper()        # MAYUSCULAS
texto.strip()        # quita espacios
texto.replace("Python", "Dev")
texto.startswith(" Hola")
texto.endswith(" ")
texto.split()        # lista de palabras


print(len(texto))    # longitud
1️⃣1️⃣ MÉTODOS DE NÚMEROS
numero = -10.7


abs(numero)        # valor absoluto
round(numero)      # redondear
round(numero, 1)   # redondear decimales


# matemáticos
import math


math.sqrt(16)      # raíz cuadrada
math.pow(2, 3)     # potencia
math.floor(4.9)    # redondeo abajo
math.ceil(4.1)     # redondeo arriba
🎯 RESUMEN VISUAL

print() → mostrar información

input() → leer datos

int(), float(), str() → convertir tipos

while → repetir con condición

for → recorrer datos

list → colecciones ordenadas

métodos str → manipular texto

métodos math → operaciones numéricas