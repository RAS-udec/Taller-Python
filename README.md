# Construyendo tu Tamagotchi-Bot desde cero 🤖🐍

Este repositorio contiene los materiales, conceptos y el desafío final del **Taller de Python** impartido por el **IEEE Robotics & Automation Society (RAS) Student Branch Chapter** de la **Universidad de Concepción**. El taller fue diseñado para la fecha 18 de Marzo de 2026.

El objetivo principal es aprender los fundamentos de la programación en Python construyendo el "cerebro" y el motor de un Tamagotchi virtual paso a paso. 

## 🛠️ Entorno de Trabajo
Para este taller no necesitas instalar nada en tu computador. Todo el código está pensado para ejecutarse en **Google Colab**, lo que permite programar y ver los resultados directamente desde el navegador de internet.

## 📚 Temario del Taller

El material teórico cubre los siguientes pilares de Python:
* **Introducción y Memoria:** Uso de la consola (`print` e `input`), variables, tipos de datos (Strings, Enteros, Booleanos) y f-strings para formateo de texto.
* **Lógica y Decisiones:** Operadores relacionales y lógicos (`and`, `or`), y control de flujo usando `if`, `elif` y `else`.
* **Estructuras de Datos:** Agrupación de información usando Listas, uso de índices (que comienzan en 0), y métodos para modificar e inspeccionar datos (`len()`, `.append()`, `.remove()`).
* **Ciclos y Repetición:** Automatización de tareas mediante bucles `for` (iteración definida) y `while` (iteración indefinida o "motor" del juego), junto con sentencias de escape como `break` y `continue`.

---

## 🚀 Mega Desafío Final: El Tamagotchi-Bot

El proyecto final consiste en programar tu propio bot interactivo. El desarrollo se divide en tres misiones de dificultad progresiva:

### 🥉 Misión Bronce: El Despertar del Núcleo
* Configuración inicial pidiendo al jugador el nombre del bot mediante un `input()`.
* Creación de un medidor de energía (comenzando en 100) y un interruptor vital lógico.
* Desarrollo del bucle principal del juego (`while True`) para mantener el programa corriendo.
* Implementación de un menú interactivo con las opciones: **[1] Jugar**, **[2] Cargar/Dormir**, o **[3] Apagar/Salir**.

### 🥈 Misión Plata: Límites Físicos y Almacenamiento
* **Límites Lógicos Anidados:** Uso de condicionales `if` dentro de otros `if` para evitar que la energía del bot supere el 100% o caiga por debajo de 0.
* **La Mochila:** Creación de un sistema de inventario mediante una lista vacía (`mochila = []`) declarada antes del bucle principal.
* Expansión del menú con la opción **[4] Explorar**, permitiendo al usuario ingresar objetos encontrados para guardarlos en la mochila usando `.append()`.

### 🥇 Misión Oro: El Easter Egg IEEE
* Inserción de un código secreto (puerta trasera) en el programa.
* Al ingresar la palabra exacta `"IEEE"` en el menú principal, se desbloquea el "Modo Desarrollador".
* Este modo secreto ajusta automáticamente la energía del bot a 9999 puntos y añade un objeto legendario (como un "Motor Cuántico de UdeC") al inventario.

---

## 👥 Sobre Nosotros
Material elaborado por la directiva del **IEEE RAS Student Branch Chapter - Universidad de Concepción**. 
¡Escanea el código QR en nuestra presentación para unirte a RAS!
