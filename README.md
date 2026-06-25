# INDICE-PRACTICAS
Se realizaron multiples practicas con el PIC16f887. En este índice se encuentran de la practica 4 a la 15

# Prácticas de Microcontroladores con PIC16F887

Repositorio que contiene las prácticas desarrolladas utilizando el microcontrolador PIC16F887, enfocadas en el manejo de entradas y salidas digitales, displays, interrupciones, LCD, conversión analógica-digital, temporizadores, PWM, motores y protocolos de comunicación.

---

# Práctica 4 - Entradas Digitales

## Objetivo

Aprender el manejo de entradas digitales mediante botones utilizando las resistencias Pull-up internas del PIC16F887.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Clase: Control de LEDs con botones

Utilización de 3 botones conectados al puerto B para controlar 3 LEDs conectados en otro puerto mediante entradas digitales y resistencias Pull-up internas.

### Actividad 1: Contador de 0 a 99

Implementación de un contador decimal de 0 a 99 utilizando dos displays de 7 segmentos, con botones para incrementar, decrementar y reiniciar el conteo.

---

# Práctica 5 - Multiplexación e Interrupciones

## Objetivo

Comprender el funcionamiento de la multiplexación de displays y el uso de interrupciones externas.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Clase 1: Contador con interrupción externa

Implementación de un contador de 0 a 9 utilizando displays de 7 segmentos. Al presionar un botón mediante interrupción externa, el contador se detiene y un LED parpadea temporalmente.

### Clase 2: Contador de 0 a 9999

Implementación de un contador de cuatro dígitos utilizando multiplexación en displays de 7 segmentos.

### Actividad 1: Contador con interrupciones

Implementación de un contador de 0 a 9999 utilizando interrupciones para incrementar el valor mostrado.

---

# Práctica 6 - Display LCD 16x2

## Objetivo

Aprender el manejo básico del display LCD 16x2 y la creación de caracteres personalizados.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Clase: Hello World

Visualización del mensaje "Hello World!" en un display LCD 16x2.

### Actividad 1: Caracteres personalizados

Creación de un carácter especial personalizado y realización de una animación al presionar un botón.

---

# Práctica 7 - Lectura Analógica

## Objetivo

Utilizar el convertidor analógico-digital (ADC) para leer señales analógicas.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Clase: Lectura de potenciómetro

Visualización del voltaje de un potenciómetro en un display LCD.

### Actividad 1: Modos de visualización

Implementación de un sistema que permite alternar entre la visualización del valor ADC, voltaje y porcentaje mediante un botón.

---

# Práctica 8 - Múltiple Lectura Analógica

## Objetivo

Realizar lecturas simultáneas de múltiples entradas analógicas.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Clase: Lectura de dos potenciómetros

Visualización de los valores de voltaje de dos potenciómetros en un display LCD.

### Actividad 1: Selección de datos y formatos

Implementación de botones para alternar entre los modos de visualización ADC, voltaje y porcentaje, así como seleccionar cuál potenciómetro mostrar en pantalla.

---

# Práctica 9 - Timer 0

## Objetivo

Comprender el funcionamiento del temporizador Timer0 para medición de tiempo.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Clase: Tiempo de ejecución

Visualización del tiempo de ejecución del microcontrolador utilizando Timer0 en un display LCD.

### Actividad 1: ADC y Timer0

Visualización simultánea del voltaje de un potenciómetro y el tiempo de ejecución del sistema.

---

# Práctica 10 - Timer 1

## Objetivo

Utilizar el temporizador Timer1 para medición precisa de intervalos de tiempo.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Clase: Tiempo de ejecución con Timer1

Visualización del tiempo de ejecución del microcontrolador utilizando Timer1 en un display LCD.

### Actividad 1: ADC y Timer1

Visualización simultánea del voltaje de un potenciómetro y el tiempo de ejecución utilizando Timer1.

---

# Práctica 11 - PWM por Hardware y PWM por Software

## Objetivo

Controlar señales PWM para regular la intensidad luminosa de LEDs.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Actividad 1: PWM por hardware

Control de la intensidad luminosa de un LED mediante un potenciómetro utilizando el módulo PWM del microcontrolador.

### Actividad 2: PWM por hardware y software

Control independiente de dos LEDs utilizando dos potenciómetros, implementando PWM por hardware y PWM por software.

---

# Práctica 12 - Teclado Matricial

## Objetivo

Aprender el manejo de teclados matriciales y la interacción con displays LCD.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Actividad 1: Visualización de teclas

Detección y visualización en LCD del carácter presionado en un teclado matricial.

### Actividad 2: Calculadora básica

Implementación de una calculadora capaz de realizar operaciones de suma, resta, multiplicación y división utilizando un teclado matricial para la entrada de datos.

---

# Práctica 13 - Motor DC

## Objetivo

Controlar motores de corriente directa mediante diferentes etapas de potencia.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Actividad 1: Control de velocidad

Control de la velocidad de giro de un motor DC mediante un circuito driver basado en transistores BJT.

### Actividad 2: Puente H

Control del sentido de giro y velocidad de un motor utilizando un puente H.

---

# Práctica 14 - Servomotores

## Objetivo

Implementar el control de posición angular de servomotores mediante PWM.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Actividad 1: Barrido angular

Control automático de un servomotor realizando un barrido desde 0° hasta 180° y regresando a la posición inicial.

### Actividad 2: Control con potenciómetro

Control del ángulo de giro de un servomotor mediante la lectura analógica de un potenciómetro.

---

# Práctica 15 - Comunicaciones

## Objetivo

Implementar la comunicación entre microcontroladores utilizando protocolos de comunicación digital.

## Software utilizado

* MPLAB X IDE
* Compilador XC8
* Proteus 8

### Actividad: Comunicación entre microcontroladores

Selección e implementación de un protocolo de comunicación para establecer el intercambio de información entre dos microcontroladores desarrollados por equipos distintos.
