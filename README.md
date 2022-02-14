# Ejercicios
## 1. Valores de las variables
### ¿Cuáles serán los valores de las variables a y b después de cada línea del siguiente algoritmo?

Inicio 

a=" ", b=" "  

   a <- 3  
   a="3", b=" "
  
   escribir("a = " & a)  
   a="3", b=" "
   
   b<-a+5  
   a="3", b="8"
   
   escribir("a = " & a & " y b = " & b)  
   a="3", b="8"
   
   a<-7 
   a="7", b="8"
   
   escribir("a = " & a & " y b = " & b)  
   a="7", b="8"
   
Fin 
a="7", b="8"

### UML

![1 uml drawio](https://user-images.githubusercontent.com/98824525/153864961-9bbace30-b428-417d-8d50-94ef6e6df789.svg)

### FLOWCHART

![1 flowchart drawio](https://user-images.githubusercontent.com/98824525/153865099-cc4a3292-217e-4a60-801a-05614aef58c3.svg)

## 2. ¿Qué se muestra?
### ¿Qué veremos al ejecutar el siguiente algoritmo?

Lo mostrado por pantalla sera:

Test , valor2 = 8

4 # 49,78

### UML

![2 uml drawio](https://user-images.githubusercontent.com/98824525/153865824-92a948cd-d656-4ce4-965f-d353e1ec4943.svg)

### FLOWCHART

![2 flowchart drawio](https://user-images.githubusercontent.com/98824525/153865876-70e766a3-8c16-45fc-b20e-64ff5e07effb.svg)

## 3. ¿Qué hace?
### ¿Qué hace este algoritmo?

Este algoritmo pide al usuario 2 valores, los asigna a dos variables, intercambia los valores de las variables y luego las esribe por pantalla

### UML

![3 uml drawio](https://user-images.githubusercontent.com/98824525/153866315-b994be98-3bfe-4c95-8511-de184f7c6fd0.svg)

### FLOWCHART

![3 flowchart drawio](https://user-images.githubusercontent.com/98824525/153866257-34303991-dbe0-4c32-8e54-638a4fb750fc.svg)


## 4. Velocidad media
### Escriba un algoritmo que calcule la velocidad media de desplazamiento del usuario.

Algo VelocidadMedia

variable distancia,tiempo: entero
varable velocidad: entero

Inicio

   #pedimos los valores
   
   distamcia <- enter("Introduzca la distancia recorrida (km). ")
   
   tiempo <- enter("Introduzca el tiempo del recorrido (min). ")
   
   #calculamos
   
   velocidad <- (distancia * 60) /tiempo
   
   escribir("Se ha desplazado a una velocidad de " & velocidad & "km/h.")
