# Introducción
### Algoritmo
Conjunto de instrucciones o pasos que sirven para llevar a cabo una acción u objetivo.

### Lenguaje de programación
Lenguaje o "idioma" usado para comunicarse con un ordenador. Incluyen un conjunto de comandos y cada uno tiene un significado.

### Programa
Conjunto de uno o más algoritmos escritos en uno o varios lenguajes de programación.

### El primer programa
Usamos el comando "print()" para escribir algo por pantalla:
```
print("Mi primer programa de Python")
``` 
El testo que queremos mostrar debe estar entre comillas dobles o simples (""  '')

# Variables
## Definición
Elemento que almacena datos y tiene su propio nombre. Las variables almacenan datos que pueden cambiar y es importante usar un nombre descriptivo para las variables.

```
# nombre = valor
precio = 45
```
## Tipos de datos
### Números enteros (int)
```
kilos_manzanas = 4
kilos_melocotones = 6
kilos_uvas = 3
```
### Números decimales o de coma flotante (float)
```
precio_manzanas = 1.65
precio_melocotones = 2.12
precio_uvas = 5.8
```
### Cadenas (String)
```
etiqueta_manzanas = "Manzana Golden"
etiqueta_melocotones = "Melocotón Calanda"
etiqueta_uvas = "Uva negra"
```
## Operaciones
Se pueden hacer operaciones en Python tanto con números directamente como con variables.
### Suma ( + ) y Resta ( - )
```
kilos_totales = kilos_manzanas + kilos_melocotones + kilos_uvas
kilos_regalo = 2
kilos_con_descuento = kilos_totales - kilos_regalo
```
### Multiplicación ( * ) y división ( / )
```
coste_manzanas = kilos_manzanas * precio_manzanas
n_personas = 3
coste_por_persona = coste_manzanas / n_personas
```
### Resto o módulo ( % )
```
print(13 % 2)
  > 1
```
### División entera ( // )
```
print(11 // 2)
  > 5
```
# Strings (Cadenas)
Hay muchas funciones ligadas a las cadenas en Python:
````
texto1 = "Soy un progrAma de Python"
texto2 = "hecho en clase!"

len(texto1)  ---> 25
texto1[1] ---> "S"
texto1[18:25] ---> "Python"
texto1.lower() ---> "soy un programa de python"
texto1.upper() ---> "SOY UN PROGRAMA DE PYTHON"
texto1.find("n") ) ---> 5
texto1.find("Python") ---> 19
texto1.find("hacker") ---> -1
texto1 + "/"  + texto2 ---> "Soy un progrAma de Python/hecho en clase!"
texto*3 ---> "Soy un progrAma de PythonSoy un progrAma de PythonSoy un progrAma de Python"

````

