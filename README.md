# Modulo 4 - TyHM II

# Estructuras Genéricas: Realimentación Negativa de Primer Orden

Este repositorio contiene la entrega del trabajo práctico sobre **Estructuras Genéricas de Realimentación Negativa de Primer Orden** en Dinámica de Sistemas, basado en el documento académico **D-4475-2** (*MIT System Dynamics in Education Project*, bajo la supervisión del Dr. Jay W. Forrester).

---

## 📌 ¿Qué se realizó en este trabajo?

### 1. Traducción y Maquetación Académica (LaTeX / Overleaf)
* Se realizó la traducción íntegra del artículo original del inglés al español, conservando la terminología técnica de Dinámica de Sistemas.
* El documento fue maquetado en **LaTeX** y compilado a través de **Overleaf**, organizando sus ecuaciones matemáticas, tablas comparativas y esquemas de niveles y flujos.

### 2. Implementación de Modelo en Vensim
* Se diseñó un modelo de simulación en **Vensim** que aplica los principios de la estructura genérica analizada.
* El modelo representa la dinámica poblacional a través de un nivel de población (`POBLACION`) regulado por un flujo de salida (`MUERTES`) dependiente de una fracción de mortalidad constante (`FRACCION DE MUERTE`) (bucle de realimentación negativa con meta implícita de cero).
* Adicionalmente, se acopla un flujo de entrada (`NACIMIENTOS`) dependiente de una tasa de natalidad en función del tiempo (`<Time>`) para contrastar la interacción entre bucles de realimentación.
* El archivo del modelo (`.mdl`) se encuentra adjunto en este repositorio.

### 3. Presentación de Diapositivas
* Se elaboró un conjunto de [diapositivas](https://docs.google.com/presentation/d/1K-isNRH55Ij5rKf_jU3Syj9XVJ9nMvBL7FU2eQXn4a4/edit?usp=sharing) conceptuales para la exposición de los puntos clave del documento.

### 4. Resumen conceptual del apunte
* Se elaboró un resumen adjuntado en formato `.pdf`.
