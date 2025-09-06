# Adaptive Telework Environment with AI-based Smart Lighting

## Overview

This project—developed as part of the IoT Master's Thesis at UNIR—focuses on designing and implementing a cyber-physical smart lamp. It integrates environmental sensors, edge-level AI, IoT connectivity, and dynamic lighting to monitor and classify workspace conditions, ultimately enhancing comfort, productivity, and well-being for remote and hybrid workers.

<img width="908" height="457" alt="Render_lamp" src="https://github.com/user-attachments/assets/e3c23c5b-15d6-4534-84e9-21c34287de9b" />


## Key Features

- Custom PCB integrating sensors: temperature, humidity, light spectrum, noise, CO₂, VOCs.
- Dynamic lighting control based on open-source WLED.
- TinyML (with Edge Impulse) model on the edge to classify environments as *good, moderate,* or *bad*.
- Real-time visualization via Datacake.
- Interactive online 3D model accessible at: https://lurmis.vercel.app/en

## Repository Structure

Here’s the layout of the project and what each part contains:

```text
HARDWARE/                  → PCB designs, schematics, Gerber files used for fabrication
PCB/                       → Specific PCB layout files (KiCad, Gerber)
Tiny Firmware/             → Minimal firmware examples or template for microcontroller
README.md                  → This documentation file
```
---

##  3D Model

Explore the interactive 3D model of the smart lamp here:
https://lurmis.vercel.app/en

##  Getting Started

1. Clone this repository.
2. Inspect the HARDWARE/ and PCB/ folders for PCB design sources.
3. Use the Tiny Firmware/ folder to explore or flash firmware.
4. Follow the README instructions in each folder to assemble, program, and visualize your setup.

---

##  Dashboard Example / Ejemplo de Dashboard

[Public Datacake Dashboard Example](https://app.datacake.de/dashboard/d/b61564c8-49cd-4808-8c22-bb57cf323bb0)

---

##  System Architecture

<img width="945" height="484" alt="image" src="https://github.com/user-attachments/assets/d104de6f-2ce4-4e7b-86a0-59acdf961c03" />


---

##  Acknowledgments

SEEEDSTUDIO Fusion PCB Service for sponsoring the manufacturing and assembly of our PCBs and UNIR – Universidad Internacional de La Rioja for the academic guidance.

---

##  License

This project is released under the [MIT License].

---

✍️ Developed by
**David Felipe Castiblanco Cantor** & **Óscar Martínez Cueto**  
Master in IoT – UNIR, 2025

------------------------------------------------------------------------

# Entorno de teletrabajo adaptativo con iluminación inteligente basada en IA

## Resumen

Este proyecto, desarrollado como parte del Trabajo Fin de Máster en IoT en la UNIR, se centra en el diseño e implementación de una lámpara inteligente ciberfísica. Integra sensores ambientales, IA de vanguardia, conectividad IoT e iluminación dinámica para monitorizar y clasificar las condiciones del espacio de trabajo, mejorando así la comodidad, la productividad y el bienestar de los trabajadores remotos e híbridos.


<img width="908" height="457" alt="Render_lamp" src="https://github.com/user-attachments/assets/e3c23c5b-15d6-4534-84e9-21c34287de9b" />

## Características principales

- PCB personalizada que integra sensores: temperatura, humedad, espectro luminoso, ruido, CO₂, COV.
- Control dinámico de la iluminación basado en WLED de código abierto. - Modelo TinyML (con Edge Impulse) en el borde para clasificar entornos como *buenos, moderados* o *malos*.
- Visualización en tiempo real mediante Datacake.
- Modelo 3D interactivo en línea disponible en: https://lurmis.vercel.app/en

## Estructura del repositorio

A continuación, se muestra el diseño del proyecto y el contenido de cada parte:

```texto
HARDWARE/ → Diseños de PCB, esquemas y archivos Gerber utilizados para la fabricación
PCB/ → Archivos específicos de diseño de PCB (KiCad, Gerber)
Tiny Firmware/ → Ejemplos mínimos de firmware o plantilla para microcontrolador
README.md → Este archivo de documentación
```
---

## Modelo 3D

Explora el modelo 3D interactivo de la lámpara inteligente aquí:
https://lurmis.vercel.app/en

## Primeros pasos

1. Clona este repositorio.
2. Revise las carpetas HARDWARE/ y PCB/ para encontrar las fuentes de diseño de PCB.

3. Use la carpeta Tiny Firmware/ para explorar o actualizar el firmware.

4. Siga las instrucciones del archivo README en cada carpeta para ensamblar, programar y visualizar su configuración.

---

## Ejemplo de Dashboard / Ejemplo de Dashboard

[Ejemplo de Dashboard Público de Datacake](https://app.datacake.de/dashboard/d/b61564c8-49cd-4808-8c22-bb57cf323bb0)

---

## Arquitectura del Sistema

<img width="945" height="484" alt="image" src="https://github.com/user-attachments/assets/d104de6f-2ce4-4e7b-86a0-59acdf961c03" />

---

## Agradecimientos

A SEEEDSTUDIO Fusion PCB Service por el patrocinio de la fabricación y el ensamblaje de nuestras PCB y a UNIR – Universidad Internacional de La Rioja por la orientación académica.

---

## Licencia

Este proyecto se publica bajo la [Licencia MIT].

---

✍️ Desarrollado por:  
**David Felipe Castiblanco Cantor** & **Óscar Martínez Cueto**  
Master in IoT – UNIR, 2025
