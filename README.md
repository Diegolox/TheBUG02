# TheBUG02

## 🇬🇧 English

**TheBUG02** is a custom **all-in-one control PCB** designed for a **two-wheel differential drive robot**.  
The project aims to provide a compact and integrated embedded platform that combines the essential hardware blocks required in a small mobile robot: power management, motor driving, microcontroller integration, battery monitoring, and development interfaces.

Instead of relying on multiple external modules, this board concentrates the complete low-level electronics into a single PCB, making the robot easier to assemble, more reliable, and better suited for rapid prototyping and iterative development.

## What the project consists of

TheBUG02 is designed as a robotics electronics platform where the main control and power subsystems are already integrated on-board. The design includes:

- **ESP32-based control system** as the main processing unit
- **Integrated motor drivers** for controlling the DC motors of the robot
- **Integrated DC-DC converter** for efficient power conversion from the battery supply
- **Integrated linear regulator** for stable regulated voltage rails
- **Battery voltage sensing** for supply monitoring and power supervision
- **ESP-PROG programming/debugging interface** for firmware upload and debugging
- **Compact full-SMD PCB design** for reduced size and improved manufacturability

## Project purpose

The purpose of TheBUG02 is to serve as a compact embedded controller for mobile robotics applications, especially small autonomous robots based on differential drive kinematics.

This board is intended to simplify the hardware side of robotics development by offering a self-contained solution that can be used for:

- Differential drive motor control
- Battery-powered robot platforms
- Embedded firmware development with ESP32
- Rapid robotics prototyping
- Autonomous navigation experiments
- Educational and research-oriented robotics projects

## Design approach

The project follows a clear design philosophy: reduce external wiring, improve electrical integration, and create a cleaner and more robust electronics architecture for mobile robots.

By integrating the power stage, motor drivers, processor, and monitoring circuitry into a single board, TheBUG02 becomes a practical base for building complete robotic systems with fewer external dependencies.

---

## 🇪🇸 Español

**TheBUG02** es una **PCB de control todo-en-uno** diseñada para un **robot diferencial de dos ruedas**.  
El proyecto busca ofrecer una plataforma embebida compacta e integrada que reúna en una sola placa los bloques electrónicos principales necesarios en un robot móvil pequeño: gestión de alimentación, accionamiento de motores, integración del microcontrolador, monitorización de batería e interfaces de desarrollo.

En lugar de depender de varios módulos externos, esta placa concentra toda la electrónica de bajo nivel en una única PCB, haciendo que el robot sea más fácil de montar, más fiable y más adecuada para prototipado rápido y desarrollo iterativo.

## En qué consiste el proyecto

TheBUG02 está planteado como una plataforma electrónica para robótica en la que los subsistemas principales de control y potencia ya vienen integrados en placa. El diseño incluye:

- **Sistema de control basado en ESP32** como unidad principal de procesamiento
- **Drivers de motores integrados** para el control de los motores DC del robot
- **Convertidor DC-DC integrado** para convertir de forma eficiente la alimentación desde batería
- **Regulador lineal integrado** para generar tensiones reguladas estables
- **Lectura de tensión de baterías** para monitorización y supervisión energética
- **Interfaz de programación y depuración ESP-PROG** para carga de firmware y debugging
- **Diseño full-SMD y compacto**, orientado a reducir tamaño y mejorar fabricabilidad

## Objetivo del proyecto

El objetivo de TheBUG02 es servir como controlador embebido compacto para aplicaciones de robótica móvil, especialmente robots pequeños basados en cinemática diferencial.

Esta placa está pensada para simplificar la parte hardware del desarrollo robótico, proporcionando una solución autocontenida que pueda utilizarse en:

- Control de robots diferenciales
- Plataformas robóticas alimentadas por batería
- Desarrollo de firmware embebido con ESP32
- Prototipado rápido en robótica
- Experimentos de navegación autónoma
- Proyectos educativos y de investigación

## Enfoque de diseño

El proyecto sigue una filosofía clara de diseño: reducir cableado externo, mejorar la integración eléctrica y construir una arquitectura electrónica más limpia y robusta para robots móviles.

Al integrar en una sola placa la etapa de potencia, los drivers de motor, el procesador y la circuitería de monitorización, TheBUG02 se convierte en una base práctica para construir sistemas robóticos completos con menos dependencias externas.

---

## Images / Imágenes

### 3D View / Vista 3D
![3D View](images/3D.png)

### PCB Layout
![PCB Layout](images/layout.png)

### Schematic / Esquemático
![Schematic](images/schematic.png)

---

## Project Status / Estado del proyecto

**Status / Estado:** In development / prototyping · En desarrollo / prototipado
