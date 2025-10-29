\# Introducción

\### Algoritmo

Conjunto de instrucciones o pasos que sirven para llevar a cabo una acción u objetivo.



\### Lenguaje de programación

Lenguaje o "idioma" usado para comunicarse con un ordenador. Incluyen un conjunto de comandos y cada uno tiene un significado.



\### Programa

Conjunto de uno o más algoritmos escritos en uno o varios lenguajes de programación.



\### El primer programa

Usamos el comando "print()" para escribir algo por pantalla:

```

print("Mi primer programa de Python")

``` 

El testo que queremos mostrar debe estar entre comillas dobles o simples (""  '')



\# Variables

\## Definición

Elemento que almacena datos y tiene su propio nombre. Las variables almacenan datos que pueden cambiar y es importante usar un nombre descriptivo para las variables.



```

\# nombre = valor

precio = 45

```

\## Tipos de datos

\### Números enteros (int)

```

kilos\_manzanas = 4

kilos\_melocotones = 6

kilos\_uvas = 3

```

\### Números decimales o de coma flotante (float)

```

precio\_manzanas = 1.65

precio\_melocotones = 2.12

precio\_uvas = 5.8

```

\### Cadenas (String)

```

etiqueta\_manzanas = "Manzana Golden"

etiqueta\_melocotones = "Melocotón Calanda"

etiqueta\_uvas = "Uva negra"

```

\## Operaciones

Se pueden hacer operaciones en Python tanto con números directamente como con variables.

\### Suma ( + ) y Resta ( - )

```

kilos\_totales = kilos\_manzanas + kilos\_melocotones + kilos\_uvas

kilos\_regalo = 2

kilos\_con\_descuento = kilos\_totales - kilos\_regalo

```

\### Multiplicación ( \* ) y división ( / )

```

coste\_manzanas = kilos\_manzanas \* precio\_manzanas

n\_personas = 3

coste\_por\_persona = coste\_manzanas / n\_personas

```

\### Resto o módulo ( % )

```

print(13 % 2)

&nbsp; > 1

```

\### División entera ( // )

```

print(11 // 2)

&nbsp; > 5

```

\# Strings (Cadenas)

Hay muchas funciones ligadas a las cadenas en Python:

````

texto1 = "Soy un progrAma de Python"

texto2 = "hecho en clase!"



len(texto1)  ---> 25

texto1\[1] ---> "S"

texto1\[18:25] ---> "Python"

texto1.lower() ---> "soy un programa de python"

texto1.upper() ---> "SOY UN PROGRAMA DE PYTHON"

texto1.find("n") ) ---> 5

texto1.find("Python") ---> 19

texto1.find("hacker") ---> -1

texto1 + "/"  + texto2 ---> "Soy un progrAma de Python/hecho en clase!"

texto\*3 ---> "Soy un progrAma de PythonSoy un progrAma de PythonSoy un progrAma de Python"



````

