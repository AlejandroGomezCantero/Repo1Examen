# Repo1Examen

# 📖 Explicación clara y comprensible del proyecto  

Una Calculadora de Conversión de Unidades que permite convertir entre diferentes unidades de medida, como longitud (metros, kilómetros, millas), peso (kilogramos, libras, onzas), temperatura (Celsius), volumen (litros, galones) y tiempo (segundos, minutos, horas).

Este proyecto es útil para aquellos que necesitan realizar conversiones rápidas entre unidades, especialmente cuando están trabajando con diferentes sistemas de medida.

## 📂 Estructura adecuada con secciones bien definidas 

**Introducción**

El Conversor de Unidades es una aplicación de consola desarrollada en Java que permite convertir diferentes tipos de unidades de medida de manera rápida y sencilla.

**Como Instalarlo**

1. *Clonamos el repositorio en la maquina local*  
   git clone https://github.com/AlejandroGomezCantero/Repo1Examen

 *![image](https://github.com/user-attachments/assets/1e37650d-39ed-422d-9ee5-378ecb34608c) *

**Uso**

Ejecuta la aplicación en la terminal para comenzar a convertir unidades.

*Ejemplos de comandos:*

*Convertir longitud:*

convertir longitud 10 metros a kilómetros

*Convertir temperatura:*

convertir temperatura 32 celsius a fahrenheit

*Convertir peso:*

convertir peso 5 kilogramos a libras

Cada comando devuelve el resultado de la conversión en la terminal.


**🛠 Uso de Ramas en Git y gitignore**

Rama1 - Cambios en Conversiones de Tiempo y Peso
En esta rama, se añadieron nuevas funcionalidades relacionadas con la conversión de unidades de tiempo y peso. Específicamente, se implementaron medidas de conversión para segundos y minutos, así como para kilogramos y gramos. Estas nuevas conversiones permiten al usuario realizar operaciones de conversión de unidades tanto para el tiempo como para el peso.

Clases modificadas/añadidas:

ConversorTiempo.java

ConversorPeso.java

Efecto en el proyecto: Esta rama mejora la funcionalidad del proyecto al permitir al usuario realizar conversiones adicionales entre diferentes unidades de tiempo y peso. Las clases se integran en el flujo principal del programa y proporcionan un conjunto más amplio de herramientas de conversión.

Rama2 - Cambios en Conversor de Agua y Eliminación de Conversor de Temperatura
En esta rama, se realizó una eliminación del archivo ConversorTemperatura.java, ya que no era necesario para el alcance del proyecto. Además, se introdujo una nueva clase denominada ConversorAgua que permite convertir entre los tres estados del agua: líquido, gaseoso y sólido. Esta nueva clase amplía la capacidad del proyecto al permitir conversiones relacionadas con los estados del agua.

Clases modificadas/añadidas:

Añadido: ConversorAgua.java

Archivo eliminado: ConversorTemperatura.java

Efecto en el proyecto: Esta rama optimiza el código al eliminar una clase innecesaria y agrega una nueva clase con funcionalidades para el estado físico del agua. Las modificaciones mejoran la flexibilidad del programa al proporcionar conversiones específicas para el agua.

**Requisitos**

Java 11 o superior.

IDE (como IntelliJ IDEA, Eclipse o NetBeans) o terminal con acceso a javac y java.

