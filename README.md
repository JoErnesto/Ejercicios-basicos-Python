# Ejercicios-basicos-Python
[Actualizado el 26-septiembre-2022 por [José Ernesto Calvillo](https://github.com/JoErnesto)]

En este repositorio se encuentran los ejercicios básicos de Python de la plataforma CodigoIoT, así como también una captura de pantalla de VSC donde se muestra el código y el resultado al correrlo.

Puedes encontrar el curso correspondiente a este ejercicio en el siguiente enlace.

https://edu.codigoiot.com/

### Requisitos
Para que el código de este repositorio funcione, es necesario contar con lo siguiente:

- Visual Studio Code
- Jupyter
- Python3
- Anaconda
- Ubuntu 20.04
- Raspberry Pi
- Sensor MLX90614

### Guías
Para configurar correctamente para trabajar con Python en Visual Studio Code en Ubuntu 20.04 puedes consultar el siguiente enlace:

https://edu.codigoiot.com/course/view.php?id=838

Para la instalación de Visual Studio Code en Ubuntu 20.04 puedes consultar el siguiente enlace:

https://edu.codigoiot.com/course/view.php?id=822

### Funcionamiento
El repositorio contiene diversos ejercicios de los siguientes temas:
- Variables en Python
- Operadores
- Funciones
- Estructuras de control
- Bibliotecas (Con Raspberry Pi y sensor MLX90614)

#### Variables en Python
Este ejercicio consiste en solicitar al usuario su color favorito, su edad y su peso, para posteriormente imprimirlos en la terminal. Esto con el fin de utilizar las variables de `Int`, `Input` y `Float`.
Foto del código y su resultado en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Variables%20Python/Variables.png)

#### Operadores
Este ejercicio consiste en solicitar al usuario un dígito y mediante un condicional If Else ver si el número ingresado pertenece a los primeros cinco números primos con el operador de igualdad `==`.
Foto del código y su resultado en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Operadores/Operadores.png)

#### Funciones
Este apartado consiste de dos ejercicios, los cuales son:

##### Funciones con Parametros
Consiste en dibujar una figura solicitando el alto y ancho de esta. Se adjunta foto del código y su resultado en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Funciones/Funciones%20con%20parametros.png)

##### Regreso de Valores
Este ejercicio consite en una función de sucesión geométrica la cual recibe 3 valores, realiza una operación y devuelve un resultado.
Se adjunta foto del código y su resultado en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Funciones/Regreso%20de%20valores.png)

#### Estructuras de Control
Este apartado está conformado por 6 ejercicios, los cuales son los siguientes:

##### 1- Iteraciones
Este ejercicio se conforma de un ciclo While, el cual se repetirá hasta encontrar un espacio en blanco de la información ingresada por el usuario. Para esto se cuenta con un condicional If que se asegura que lo ingresado por el usuario sea correcto para el funcionamiento del programa. Se adjunta foto del código y la respuesta en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Estructuras%20de%20control%20Python/Iteraciones.png)

##### 2- If-Else
Este ejercicio consiste en solicitar al usuario un número, para luego revisar si este es igual `==` a 0 si es diferente a este. Se adjunta foto del código y su resultado en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Estructuras%20de%20control%20Python/If-Else.png)

##### 3- If-Elif-Else
El ejercicio consiste en solicitar al usuario un número, si este es mayor a 0 `> 0` se imprime en terminal `El número es positivo`, si es menor a 0 `< 0` se imprime en terminal `El número es negativo` y si no es ninguno de los anteriores se imprime los siguiente `El número es cero`. Se adjunta foto del código y respuesta en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Estructuras%20de%20control%20Python/If-Elif-Else.png)

##### 4- For
Este ejercicio consiste en utilizar el ciclo `For`, en el cual el usuario ingresa un número mayor a 3 y el programa le devuelve los multiplos de 3. Se adjunta foto del código y su resultado en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Estructuras%20de%20control%20Python/For.png)

##### 5- Estructura de Control Anidadas
Este ejercicio consiste en solicitar un número al usuario para determinar si este es `grande`, `muy grande`, `si es negativo` o si `es cero`. Se adjunta foto del código y resultado en terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Estructuras%20de%20control%20Python/Estructuras%20de%20control%20anidadas.png)

##### 6- Bucle Anidado
En este último ejercicio de Estructuras de Control Python se utilizan 3 ciclos `For` en los cuales se realizan una operación y se repite con el resltado de la iteración antrior. Se adjunta foto del código y terminal:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Estructuras%20de%20control%20Python/Bucle%20anidado.png)

#### Bibliotecas
Para este ejercicio se utilizó la Raspberry Pi 4 y el sensor MLX90614 con el objetivo de realizar un programa en Python el cual lea la temperatura de un objeto por ifrarrojo y también la del ambiente, posteriormente las imprima por terminal. Para este ejercicio se requiere habilitar la comunicación I2C de la Raspberry y realizar las conexiones al sensor, para ello se utilizó el siguiente diagrama de los pines de salida de la Raspberry.
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Bibliotecas/R-Pi-4-GPIO-Pinout.jpg)
Las conexiones realizadas son las siguientes:
`Rasp/Sensor`
`5V/VCC`
`GND/GND`
`GPIO2/SDA`
`GPIO3/SCL`
Se adjunta foto del las lecturas realizadas:
![](https://github.com/JoErnesto/Ejercicios-basicos-Python/blob/main/Bibliotecas/Bibliotecas%20MLX90614.png)

## Evidencias

- [YouTube]()

# Créditos

Desarrollado por José Ernesto Calvillo Lizárraga
- [GitHub](https://github.com/JoErnesto)
- [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-ernesto-calvillo-liz%C3%A1rraga-4188a4231/)