# Construyendo tu Tamagotchi-Bot desde cero 🤖🐍

[cite_start]Este repositorio contiene los materiales, conceptos y el desafío final del **Taller de Python** impartido por el **IEEE Robotics & Automation Society (RAS) Student Branch Chapter** de la **Universidad de Concepción**[cite: 6, 7, 216, 218, 219]. [cite_start]El taller fue diseñado para la fecha 18 de Marzo de 2026[cite: 8, 220].

[cite_start]El objetivo principal es aprender los fundamentos de la programación en Python construyendo el "cerebro" y el motor de un Tamagotchi virtual paso a paso[cite: 187, 188, 646]. 

## 🛠️ Entorno de Trabajo
[cite_start]Para este taller no necesitas instalar nada en tu computador[cite: 15]. [cite_start]Todo el código está pensado para ejecutarse en **Google Colab**, lo que permite programar y ver los resultados directamente desde el navegador de internet[cite: 15, 254].

## 📚 Temario del Taller

El material teórico cubre los siguientes pilares de Python:
* [cite_start]**Introducción y Memoria:** Uso de la consola (`print` e `input`), variables, tipos de datos (Strings, Enteros, Booleanos) y f-strings para formateo de texto[cite: 10, 34, 35, 36, 49].
* [cite_start]**Lógica y Decisiones:** Operadores relacionales y lógicos (`and`, `or`), y control de flujo usando `if`, `elif` y `else`[cite: 10, 58, 59, 67].
* [cite_start]**Estructuras de Datos:** Agrupación de información usando Listas, uso de índices (que comienzan en 0), y métodos para modificar e inspeccionar datos (`len()`, `.append()`, `.remove()`)[cite: 10, 94, 106, 158, 159].
* [cite_start]**Ciclos y Repetición:** Automatización de tareas mediante bucles `for` (iteración definida) y `while` (iteración indefinida o "motor" del juego), junto con sentencias de escape como `break` y `continue`[cite: 10, 115, 119, 125, 126].

---

## 🚀 Mega Desafío Final: El Tamagotchi-Bot

[cite_start]El proyecto final consiste en programar tu propio bot interactivo[cite: 185, 187]. [cite_start]El desarrollo se divide en tres misiones de dificultad progresiva[cite: 647]:

### 🥉 Misión Bronce: El Despertar del Núcleo
* [cite_start]Configuración inicial pidiendo al jugador el nombre del bot mediante un `input()`[cite: 191].
* [cite_start]Creación de un medidor de energía (comenzando en 100) y un interruptor vital lógico[cite: 192].
* [cite_start]Desarrollo del bucle principal del juego (`while True`) para mantener el programa corriendo[cite: 657].
* [cite_start]Implementación de un menú interactivo con las opciones: **[1] Jugar**, **[2] Cargar/Dormir**, o **[3] Apagar/Salir**[cite: 194, 658].

### 🥈 Misión Plata: Límites Físicos y Almacenamiento
* [cite_start]**Límites Lógicos Anidados:** Uso de condicionales `if` dentro de otros `if` para evitar que la energía del bot supere el 100% o caiga por debajo de 0[cite: 201, 202, 668].
* [cite_start]**La Mochila:** Creación de un sistema de inventario mediante una lista vacía (`mochila = []`) declarada antes del bucle principal[cite: 203, 204].
* [cite_start]Expansión del menú con la opción **[4] Explorar**, permitiendo al usuario ingresar objetos encontrados para guardarlos en la mochila usando `.append()`[cite: 206, 208, 669, 670].

### 🥇 Misión Oro: El Easter Egg IEEE
* [cite_start]Inserción de un código secreto (puerta trasera) en el programa[cite: 210, 678].
* [cite_start]Al ingresar la palabra exacta `"IEEE"` en el menú principal, se desbloquea el "Modo Desarrollador"[cite: 210, 211, 680].
* [cite_start]Este modo secreto ajusta automáticamente la energía del bot a 9999 puntos y añade un objeto legendario (como un "Motor Cuántico de UdeC") al inventario[cite: 212, 213, 680].

---

## 👥 Sobre Nosotros
[cite_start]Material elaborado por la directiva del **IEEE RAS Student Branch Chapter - Universidad de Concepción**[cite: 7]. 
[cite_start]¡Escanea el código QR en nuestra presentación para unirte a RAS! [cite: 687]
