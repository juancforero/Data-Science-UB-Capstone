# Data-Science-UB-Capstone

**Trading de Alta Frecuencia**

**1. Introduccion**


* Definición
Es un tipo de trading donde las decisiones de inversión tienen un horizonte temporal más pequeño, minutos o incluso segundos, allí las determinaciones de inversión deben ser ejecutadas por algoritmos precisamente por la estrechez de ese horizonte temporal.

* Importancia
Se estima que entre el 60 y 70 % de todas las operaciones realizadas en los mercados de acciones —60 % del mercado de futuros y un 50 % en el mercado de treasury bonds americanos— son realizadas por algún tipo de algoritmo. Además, se estima que para el 2026 el valor de las operaciones diarias realizadas por algoritmos alcance US 21.52 billones tomando como base el 2019 con una cifra promedio de US 9.53 billones (Research, 2020).

**2. Fuente de datos**

* se ha decidido utilizar OANDA como bróker para la obtención de datos. En particular, OANDA es una plataforma de trading para traders de retail (traders no institucionales). Se ha escogido esta plataforma por tres razones fundamentales:
En primer lugar, es una plataforma que tiene una gran cantidad de activos.Tiene 150 diferentes tipos de activos de los que podemos obtener información, de allí podremos adquirir sus series históricas con diferentes intervalos de tiempo, es decir, tickers de un 
do, un minuto, una hora, etcétera.  

* En segundo lugar, se escogió esta plataforma porque la profundidad del mercado también es importante a la hora de evaluar el comportamiento de un activo, por lo cual es importante tener una plataforma que tenga grandes volúmenes de transacciones y que de alguna manera el precio de los activos refleje los volúmenes de negociación. 

* tercer lugar, he escogido esta plataforma por las facilidades de brinda para la extracción de datos y las API que ofrece para su extracción en diferentes en lenguajes. Toda la estrategia estará programada en Python y las peticiones al servidor de la aplicación se realizarán por medio de un script también programado en este lenguaje

* Periodo: 23 de mayo del 2019 – 5 de mayo 2021
* Granularidad: 5 minutos
* Total, datos = 140.000 ticks
* Datos de validación: 60 % = 84000 ticks
* Datos de prueba: 20 % = 28.000
* Datos de validación: 10 % = 14.000

Características principales
* EUR/USD:  Euros por dólar americano
* EUR/SGD:  Euros por dólar de Singapur
* EUR/GBP:  Euros por Libras Esterlinas
* EUR/CAD:  Euros por dólar canadiense
* EUR/HKD:  Euros por dólar Hongkonés

**2. Estructura del Libro**

**2.1 Conexion Api Onda**
* conexion y data retrieval
* Organizacion  y filtro de datos
* Almacenaniento de datos en Base de datos local

**2.2. Manipulacion de datos y medidas de error**

* **Estandaraizacion**

- Minmax Escaler

* **Error de Modelo**
- Mean Absolute Error

* **Desempeño del Algoritmo**

- Total Return


**3. Algoritmos**

* Redes Neuronales LSTM (long short-term memory networks) 
* Red Neuronal Convolucional Completamente conectada con LSTM
* Red Neuronal Convolucional Completamente conectada con LSTM Clasificación

**4. Resultados y Evaluacion**



