# Curso Básico de Python

- [Curso Básico de Python](#curso-básico-de-python)
  - [Modulo 1 Introduccion a la programacion con Python](#modulo-1-introduccion-a-la-programacion-con-python)
    - [Clase 1 EL arte de la programacion](#clase-1-el-arte-de-la-programacion)
    - [Clase 2 Por que Python](#clase-2-por-que-python)
    - [Clase 3 El núcleo de un programa: los algoritmos](#clase-3-el-núcleo-de-un-programa-los-algoritmos)
    - [Clase 4 Instalación de nuestras herramientas (en Windows)](#clase-4-instalación-de-nuestras-herramientas-en-windows)
    - [Clase 5 Instalacion de nuestras herramientas en Mac](#clase-5-instalacion-de-nuestras-herramientas-en-mac)
    - [Clase 6 Instalacion de nuestras herramientas en Ubuntu](#clase-6-instalacion-de-nuestras-herramientas-en-ubuntu)
    - [Clase 7 Tu mejor herramienta: la consola](#clase-7-tu-mejor-herramienta-la-consola)
  - [Modulo 2 Conceptos basicos de Python](#modulo-2-conceptos-basicos-de-python)
    - [Clase 8 Explorando Python: operadores aritméticos](#clase-8-explorando-python-operadores-aritméticos)
    - [Clase 9 Que es una variable](#clase-9-que-es-una-variable)
    - [Clase 10 Los primitivos: tipos de datos sencillos](#clase-10-los-primitivos-tipos-de-datos-sencillos)
    - [Clase 11 Convertir un dato a un tipo diferente](#clase-11-convertir-un-dato-a-un-tipo-diferente)
    - [Clase 12 Operadores logicos y de comparacion](#clase-12-operadores-logicos-y-de-comparacion)
    - [Clase 13 Tu primer programa: conversor de monedas](#clase-13-tu-primer-programa-conversor-de-monedas)
  - [Modulo 3 Herramientas para programar](#modulo-3-herramientas-para-programar)
    - [Clase 14 Construyendo el camino de un programa con condicionales](#clase-14-construyendo-el-camino-de-un-programa-con-condicionales)
    - [Clase 15 Varios paises en mi conversor de monedas](#clase-15-varios-paises-en-mi-conversor-de-monedas)
    - [Clase 16 Aprendiendo a no repetir codigo con funciones](#clase-16-aprendiendo-a-no-repetir-codigo-con-funciones)
    - [Clase 17 Modularizando nuestro conversor de monedas](#clase-17-modularizando-nuestro-conversor-de-monedas)
    - [Clase 18 Trabajando con texto: cadenas de caracteres](#clase-18-trabajando-con-texto-cadenas-de-caracteres)
    - [Clase 19 Trabajando con texto: slices](#clase-19-trabajando-con-texto-slices)
    - [Clase 20 Proyecto: palindromo](#clase-20-proyecto-palindromo)
  - [Modulo 4 Bucles](#modulo-4-bucles)
    - [Clase 21 Aprendiendo bucles](#clase-21-aprendiendo-bucles)
    - [Clase 22 El ciclo while](#clase-22-el-ciclo-while)
    - [Clase 23 Explorando un bucle diferente: el ciclo for](#clase-23-explorando-un-bucle-diferente-el-ciclo-for)
    - [Clase 24 Recorriendo un string con for](#clase-24-recorriendo-un-string-con-for)
    - [Clase 25 Interrumpiendo ciclos con break y continue](#clase-25-interrumpiendo-ciclos-con-break-y-continue)
    - [Clase 26 Proyecto: prueba de primalidad](#clase-26-proyecto-prueba-de-primalidad)
    - [Clase 27 Proyecto: videojuego](#clase-27-proyecto-videojuego)
  - [Modulo 5 Estructuras de datos](#modulo-5-estructuras-de-datos)
    - [Clase 28  Almacenar varios valores en una variable: listas](#clase-28-almacenar-varios-valores-en-una-variable-listas)
    - [Clase 29 Entendiendo cómo funcionan las tuplas](#clase-29-entendiendo-cómo-funcionan-las-tuplas)
    - [Clase 30 Que son los diccionarios](#clase-30-que-son-los-diccionarios)
    - [Clase 31 Proyecto: generador de contrasenas](#clase-31-proyecto-generador-de-contrasenas)

## Modulo 1 Introduccion a la programacion con Python

### Clase 1 EL arte de la programacion

Programar es darle instrucciones a la computadora para que realce un trabajo especifico.

### Clase 2 Por que Python

Antes de elegir un nuevo lenguaje para aprender debemos pensar primero que queremos lograr o realizar (ciencia de datos, backend, frontend, desarrollo de videojuegos, desarrollo movil, iot, DevOps, etc).

Python esta en todos lados (google, spotify, platzi, etc)

Ventajas:

- Fácil
- Elegante
- Buenas practicas

### Clase 3 El núcleo de un programa: los algoritmos

 Algoritmo se define por tener estas caracteristicas:

- Una serie de  pasos para resolver un problema
- Finito
- No ambiguo

### Clase 4 Instalación de nuestras herramientas (en Windows)

1.- Instalacion del editor de código de tu elección. (VScode)
2.- Uso de terminal, el profesor utiliza cmder (me quedo con ubuntu)
3.- Instalacion de python 3

### Clase 5 Instalacion de nuestras herramientas en Mac

Nota: Si usas una mac el proceso es el mismo para instalar cualquier programa, descarga e instala VScode y python3.

### Clase 6 Instalacion de nuestras herramientas en Ubuntu

Nota: Si usas una distro de linux el proceso es el mismo para instalar cualquier programa, descarga e instala VScode y python3.

### Clase 7 Tu mejor herramienta: la consola

Comandos básicos Unix

1.- control+L (Limpieza a la consola)
2.- mkdir mi_carpeta (Crear carpeta)
3.- ls (Listar archivos y directorios del directorio actual)
4.- cd mi_carpeta (Ingresar a la nueva carpeta)

Para profundizar en comandos (si eres nuevo usuario) mira el curso de termina y linea de comandos en platzi.
<https://platzi.com/clases/terminal/>

## Modulo 2 Conceptos basicos de Python

### Clase 8 Explorando Python: operadores aritméticos

Usando la consola interactiva de python realizamos lo siguiente

```py
#Suma (+)
>>> 5+5
5

#Resta (-)
>>> 5-5
0

#Multiplicación (#)
>>> 5*5
25

#División (/)
>>> 21/5
4.2

#División entera (//), Esta nos trae el numero entero de la division
>>> 21 // 5
4

#Modulo (%), Este nos trae el residuo de la division
>>> 21 % 5
1

#Potencia (**)
>>> 2 ** 2
4

#Python respeta las reglas matemáticas que dice
>>> 5 + 5 * 2
15
```

Python siempre sigue el orden de las operaciones aritméticas, ante la duda siempre recuerda PEMDAS.

**P**aréntesis
**E**xponentes
**M**ultiplicación
**D**ivisión
**A**dición
**S**ustracción.

### Clase 9 Que es una variable

Una variable es una caja donde puedes guardar un objeto, cada variable tiene un identificador en memoria

```py
>>> numero = 3
>>> print(numero)
3
>>> numero2 = 5
>>> numero3 = numero + numero2
>>> print(numero)
8
```

Reglas para variables

- nunca iniciar con números o símbolos
- usar minúsculas si solo es una palabra
- usar camel_case si son varias palabras

### Clase 10 Los primitivos: tipos de datos sencillos

En python todo es un objeto

Los tipos de datos primitivos en python:

- int: entero (3)
- float: números con punto flotante (4.0)
- str: cadenas de texto o strings ('hola mundo')
- bool: booleano (1 o 0), (True o False)

### Clase 11 Convertir un dato a un tipo diferente

En python podemos convertir  a conveniencia los tipos de datos primitivos

```py
#Convertir un dato a un tipo diferente
>>> nombre_variable = input( “Ingresa texto”)
>>> numero1 = input(“Escribe un numero:”)

>>> print(numero1)
'4’

>>> numero2 = input(“Escribe un numero”)
>>> print(2)
'5’


#Si sumas
>>> print(numero + numero 2)
'45’

#PARA CONVERTIRLO A NUMERO
>>> numero1 = int(numero1)
>>> numero2 = int(numero2)

>>> print(numero1 + numero2)
9

#CONVERTIR DE NUMERO A TEXTO
str(numero1)
'4'
```

### Clase 12 Operadores logicos y de comparacion

- **and** para comparar si dos valores son verdaderos.
- **or** para comparar si dos valores son falsos.
- **not** para invertir el valor booleano.
- **==** Compara dos valores y te dice si son iguales o no.
- **!=** Compara dos valores y te dice sin son diferentes o no.
- **>** Compara si es mayor que otro valor.
- **>** Compara si es menor que otro valor.
- **>=** igual o mayor que el valor a comparar.
- **<=** igual o menor que el valor a comparar

Ejemplos de la clase en consola interactiva de python

```py
>>> es_estudiante = True
>>> es_estudiante
True
>>> trabaja = False
>>> es_estudiante and trabaja
False
>>> es_estudiante or trabaja
True
>>> not trabaja
True
>>>
>>> numero1 = 5
>>> numero2 = 5
>>> numero1
5
>>> numero2
5
>>> numero1 == numero2
True
>>> numero3 = 7
>>> numero1 == numero3
False
>>> numero1 != numero3
True
>>> numero1 > numero3
False
>>> numero1 < numero3
True
>>> numero1 >= numero3
False
>>> numero1 >= numero2
True
>>> numero1 <= numero2
True
>>> numero1 <= numero3
True
>>>
```

### Clase 13 Tu primer programa: conversor de monedas

```py
# Convertir pesos a dolares
pesos = input("¿Cuántos pesos tienes? ")
pesos = float(pesos)
valor_dolar = 22.03
dolares = pesos / valor_dolar
dolares = round(dolares, 2)
dolares = str(dolares)

print("Tienes $" + dolares + " dolares")



# Convertir dolares a pesos
dolares = input("¿Cuántos dolares tienes? ")
dolares = float(dolares)
valor_pesos = 22.03
pesos = dolares * valor_dolar
pesos = round(pesos, 2)
pesos = str(pesos)

print("Tienes $" + pesos + "pesos")```
```

## Modulo 3 Herramientas para programar

### Clase 14 Construyendo el camino de un programa con condicionales

```py
# # Ejemplo 1
# edad = int(input ("Escribe tu edad :"))
# if edad > 17:
#     print("Eres mayor de edad")
# else:
#     print("Eres menor de edad")

# Ejemplo 2
numero = int(input("Escribe un numero : "))

if numero > 5:
    print("Es mayor a 5")
elif numero == 5:
    print("Es igual a 5")
elif numero < 5:
    print("Es menor a 5")

```

### Clase 15 Varios paises en mi conversor de monedas

```py
# conversor de pesos a dolares

menu = """
Bienvenido al conversor de monedas

1 - Pesos Colombianos
2 - Pesos Argentinos
3 - Pesos Mexicanos

Elige una opción: """

opcion = int(input(menu))

if opcion == 1:
    pesos = input("¿Cantos pesos colombianos tienes?:  ")
    pesos = float(pesos)
    valor_dolar = 3679
    dolares = pesos / valor_dolar
    dolares = round(dolares, 2)
    dolares = str(dolares)
    print("Tienes $" + dolares + " dólares")
elif opcion == 2:
    pesos = input("¿Cantos pesos argentinos tienes?:  ")
    pesos = float(pesos)
    valor_dolar = 65
    dolares = pesos / valor_dolar
    dolares = round(dolares, 2)
    dolares = str(dolares)
    print("Tienes $" + dolares + " dólares")
elif opcion == 3:
    pesos = input("¿Cantos pesos argentinos tienes?:  ")
    pesos = float(pesos)
    valor_dolar = 24
    dolares = pesos / valor_dolar
    dolares = round(dolares, 2)
    dolares = str(dolares)
    print("Tienes $" + dolares + " dólares")
```

### Clase 16 Aprendiendo a no repetir codigo con funciones

```py
# def imprimir_mensaje():
#     print("Mensaje Especial : ")
#     print("¡Estoy aprendiendo a usar funciones!")

# imprimir_mensaje()
# imprimir_mensaje()
# imprimir_mensaje()

def conversacion(mensaje):
    print("Hola")
    print("Como estas")
    print(mensaje)
    print("a Dios!")



opcion = int(input("Elije una opcion: (1,2,o 3) "))
if opcion == 1:
    conversacion("Elegiste la opcion 1")
elif opcion == 2:
    conversacion("Elegiste la opcion 2")
elif opcion == 3:
    conversacion("Elegiste la opcion 3")
else:
    print("Escribe la opcion correcta")
```

### Clase 17 Modularizando nuestro conversor de monedas

Esta clase hace la introduccion del keyword return, retorna el valor de una funcion.

```py
#Este programa convierte una cantidad de dolares a pesos mexicanos

#Primero definimos nuestras funciones
def conversor(tipo_pesos,valor_dolar):
    pesos = input("¿Cuantos pesos " + tipo_pesos + " convertirás? ")
    pesos = float(pesos)
    dolares = pesos / valor_dolar
    dolares = round(dolares,2)
    dolares = str(dolares)
    pesos = input("Tienes " + dolares + " dolares")


# Pedimos al usuario la cantidad que solares a convertir
menu = """ Bienvenido al conversor de monedas 💰

1 - Pesos colombianos
2 - Pesos argentinos
3 - Pesos mexicanos

Elije una opciones : """

opcion = int(input(menu))
if opcion == 1:
    conversor("colimbianos",3875)
elif opcion == 2:
    conversor("argentinos",65)
elif opcion == 3:
    conversor("mexicanos",24)
else:
    print("Opcion incorrecta, Gracias por participar")
```

### Clase 18 Trabajando con texto: cadenas de caracteres

**Método:** es una funcion especial  para un tipo de dato en particular.

```py
#METODOS:
variable.upper() #Todos los caracteres en MAYÚSCULAS
variable.capitalize() #solo la primera en MAYÚSCULA
variable.lower() = 'todos los caracteres en minúscula'
variable.strip() = #eliminar espacios basura del string al inicio y final
variable.replace('caracter_a_cambiar', 'caracter_por_poner') #remplazar caracter

#FUNCIONES BILT-IN
aquellas que son propias del lenguaje y que no tenemos que crearlas, solo invocarlas.

len()
print()
input()

#Indices
# Siempre podemos acceder a los caracteres de un string por su indice
>>> nombre='rusbel'
>>> nombre[0]
'r'

>>> nombre[1]
'u'

>>> nombre[2]
's'
```

### Clase 19 Trabajando con texto: slices

Los slices o rebanadas son una extension de los indices,  usando el key ":" permite indicar a python del string dame la información desde el indice uno hasta el indice 10 [1:10], podemos agregar pasos para ir de dos en dos, dos en tres [1:10:2] o al revés [1:10:-1]

```py
>>> nombre = "Francisco"
>>> nombre
'Francisco'
>>> nombre[0]
'F'
>>> nombre[1]
'r'
>>> nombre[0:3]
'Fra'
>>> nombre[:3]
'Fra'
>>> nombre[3:]
'ncisco'
>>> nombre[1:7]
'rancis'
>>> nombre[1:7:2]
'rni'
>>> nombre[ :: ]
'Francisco'
>>> nombre[1::3]
'rcc'
>>> nombre[::-1]
'ocsicnarF'
>>>
```

### Clase 20 Proyecto: palindromo

```py
def palindromo(palabra):
    palabra = palabra.lower()
    palabra = palabra.replace(' ', '')
    if palabra == palabra[::-1]:
        returnTrue
    else:
        returnFalse


def run():
    palabra = input("Por favor, ingresa una frase o palabra: ")
    if palindromo(palabra):
        print("Es un palíndromo")
    else:
        print("No es un palíndromo")


if __name__ == '__main__':
    run()
```

`if __name__ == '__main__'` es el entry-point de los programas en python, si internamente el nombre de este programa es main, ejecuta el codigo debajo de este, los modulos de python (programas de python en carpetas llamados por el script principal) no tienen esta instrucción.  

## Modulo 4 Bucles

### Clase 21 Aprendiendo bucles

Un bucle es un ciclo continuo en todos los lenguajes de programacion, que nos permite iterar sobre nuestros pasos, imagina un contador cíclico (1,2,3,4,5,6...) donde puedes agregar un paso mas sobre tu programa principal.

Un bucle de la vida real

- Despertar
- Estudiar en platzi
- Comer
- Dormir

Cuando repetimos estas acciones en ese orden, durante un tiempo determinado o infinito estamos hablando de un bucle.

### Clase 22 El ciclo while

```py
def run():
    LIMITE = 1000000
    contador = 0
    potencia_2 = 2**contador
    while potencia_2 < LIMITE:
        print('2 elevado a ' + str(contador) +
              ' es igual a: ' + str(potencia_2))
        contador = contador + 1
        potencia_2 = 2**contador

if __name__ == "__main__":
    run()
```

### Clase 23 Explorando un bucle diferente: el ciclo for

```py
def imprimir_numero(inicio, fin):
    for inicio in range(fin+1):
        print(f'Numero: {inicio}')


def imprimir_numero_while(inicio, fin):
    while inicio <= fin:
        print(f'Numero: {inicio}')
        inicio += 1

def run():


    while True:
        print('')
        print('*********************************************************')
        print('*******************N U M E R O S**********************')
        print('')
        inicio = int(input('Digite el número inicial para la secuencial:  '))
        print('')
        fin = int(input('Digite el número final para la secuencial: '))
        print('')

        if inicio < fin:
            imprimir_numero(inicio,fin)
        else:
            print(f'El numero inicial {inicio} debe ser ser menor al numero final {fin}.')



if __name__ == "__main__":
    run()
```

### Clase 24 Recorriendo un string con for

Ejemplo 1

```py
def run():
    ## Este ejemplo imprime cada caracter de tu nombre
    nombre = input("Escribe tu nombre :")
    for letra in nombre:
        print(letra)

if __name__ == "__main__":
    run()

```

Ejemplo 2

```py
def run():
    frase = input("Escribe una frase : ")
    for caracter in frase:
        print(caracter.upper())



if __name__ == "__main__":
    run()

```

### Clase 25 Interrumpiendo ciclos con break y continue

Ejemplo1

```py
def run():
    for i in range(10000):
        print(i)
        if i == 5678:
            break

if __name__ == '__main__':
    run()
```

ejemplo 2

```py
def run():
    for contador in range(1000):
        if contador % 2 != 0:
            continue
        print(contador)

if __name__ == '__main__':
    run()
```

ejemplo 3

```py
def run():
    texto= input('Escribe un texto: ')
    for letra in texto:
        if letra == 'o':
            break
        print(letra)

if __name__ == '__main__':
    run()
```

### Clase 26 Proyecto: prueba de primalidad

```py
def es_primo(numero):
    if numero == 1:
        return False
    else:
        contador = 0
    for i in range(1 , numero+1):
        if i == 1 or i == numero:
            continue
        if numero % i == 0:
            contador += 1
    if contador == 0:
        return True
    else:
        return False


def run():
    numero = int(input("Escribe un número: "))
    if es_primo(numero):
        print(str(numero) + " es primo")
    else:
        print(str(numero) +  " NO es primo")


if __name__ == "__main__":
    run()
```

### Clase 27 Proyecto: videojuego

```py
import random

def run():
    numero_aleatorio = random.randint(1, 100)
    numero_elegido = int(input("Elije un numero del 1 al 100 :"))
    while numero_elegido != numero_aleatorio:
        if numero_elegido < numero_aleatorio:
            print("Busca un numero mas grande ")
        else:
            print("Busca un numero mas pequeño ")
        numero_elegido = int(input("Elije otro numero  :"))
    print("Ganaste!")


if __name__ == "__main__":
    run()
```

## Modulo 5 Estructuras de datos

### Clase 28  Almacenar varios valores en una variable: listas

Las listas pertenecen a las estructuras de datos en python, pueden almacenar distintos tipos de primitivos u otras estructuras de datos dentro de una misma lista

```py
#declarar lista
my_lista = []
my_lista = list()

#unir listas
my_lista = [1]
my_lista2 = [2,3,4]
my_lista3 = my_lista + my_lista2
my_lista3 # [1,2,3,4]

#partir listas como slices
my_lista = [1,2,3]
my_lista[1:] = [2,3]

#extender una lista
my_lista = [1]
my_lista2 = [2,3,4]
my_lista.extend(my_lista2) # [1,2,3,4]

#multiplicar listas
my_lista = ['a']
my_lista2 = my_lista * 5
my_lista2 # ['a','a','a','a','a']

#eliminar ultimo elemento de la lista
my_lista = [1,2,3,4,5]
my_lista = my_lista.pop()
my_lista # [1,2,3,4]

#ordenar lista
my_lista = [2,1,5,4,3]
my_lista = my_lista.sort()
my_lista # [1,2,3,4,5]

#eliminar un elemento
my_lista = [1,2,3,4,5]
del my_lista[0]
my_lista # [2,3,4,5]

#eliminar si conocemos su valor
my_lista = [1,2,3,4,5]
my_lista.remove(3)
my_lista #[1,2,4,5]

#saber que metodos hay dentro de un elemento
my_lista = [1,2,3,4,5]
dir(my_lista) # ['__add__', '__class__', '__contains__', ...

#modificar un elemento
my_lista = [1,2,3,4,5]
my_lista[0] = 100
my_lista # [100,2,3,4,5]

#añadir un elemento al final
my_lista = [1,2,3,4,5]
my_lista.append(6)
my_lista # [1,2,3,4,5,6]

#organizar una lista
my_lista = [2,5,1,3,4]
my_lista.sort() #[1,2,3,4,5]

```

ALgunos metodos adicionales

```py
.sorted() # También ordena como sort() pero modifica la lista inicial
.clear() # vaciá la lista
.count() # Cuenta las veces que esta un elemento en lista
.index() #--> Indica la posición donde esta un elemento de la lista
.insert() #--> Inserta un elemento en una posición dada ej: lista.insert(posición,item)
.reverse() #--> Le da la vuelta a una lista
```

### Clase 29 Entendiendo cómo funcionan las tuplas

Las tuplas son estructuras de datos inmutables es decir, no puedes modificar una tupla "a" agregando o quitando un valor, lo único que puedes hacer es definir de nuevo esa tupla "a". Los objetos inmutables (como los strings) son tipos de datos para python que apuntan a un lugar especifico en memoria y que su contenido no puede ser cambiado, al cambiar el contenido predefiniendo el contenido de la variable "a" entonces cambiara su posición en memoria.

```py
#declarar tupla
mi_tupla = ()
mi_tupla = (1,2,3)

#generar una tupla de 1 solo valor (Obligatorio la ,)
mi_tupla = (1,)

#acceder a un indice de la tupla
mi_tupla = (1,2,3)
mi_tupla[0] #1
mi_tupla[1] #2
mi_tupla[2] #3

#reasignar una tupla
mi_tupla = (1,2,3)
mi_otra_tupla = (4,5,6)
mi_tupla =+ mi_otra_tupla

#metodos de las tuplas
mi_tupla = (1,1,1,2,2,3)
mi_tupla.count(1) #3 el numero 1 aparece 3 veces en la tupla
mi_tupla.index(3) #5 indice de la primera instancia donde se encuentra un elemento
mi_tupla.index(1) #0
mi_tupla.index(2) #3
```

### Clase 30 Que son los diccionarios

```py
# Definir función principal
def run():
    # Defino el diccionario, agrego los valores.
    mi_diccionario = {
      'llave1' : 1,
      'llave2' : 2,
      'llave3' : 3,
    }


    # Imprimo las llaves del diccionario utilizando una bucle for
    # Con '.keys()' estoy llamando a imprimir las llaves, no los valores.
    for llave in mi_diccionario.keys():
        print(llave)

    # Imprimo los valores del diccionario utilizando una bucle for
    # Con '.values()' estoy llamando a imprimir los valores.
    for valores in mi_diccionario.values():
        print(valores)

    # Imprimir las llaves y los valores utilizando '.items()'
    # Para esto, coloco las variables llave e items
    for llave, items in mi_diccionario.items():
        print("La llave: '" + llave + "' contiene el item: " + str(items))


if __name__ == '__main__':
    run()
```

### Clase 31 Proyecto: generador de contrasenas

```py
def generar_contrasena():
    mayusculas = ["A","B","C","D","E","F","G","H"]
    minusculas = ["a","b","c","d","e","f","g","h"]
    simbolos = ["!","@","#","$","%","&","/"]
    numeros = ["1","2","3","4","5","6","7","8","9","0"]
    caracteres = mayusculas + minusculas + simbolos + numeros
    contrasena = []
    for i in range(15):
        caranter_ramdom = random.choice(caracteres)
        contrasena.append(caranter_ramdom)
    # convertir una lista a string
    contrasena = "".join(contrasena)
    return contrasena

def run():
    contrasena = generar_contrasena()
    print("Tu nueva contraseña es: " + contrasena)


if __name__ == "__main__":
    run()
```
