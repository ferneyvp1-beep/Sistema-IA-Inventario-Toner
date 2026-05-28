# Sistema Inteligente de Inventario y Predicción de Tóner

## Descripción del Proyecto

Este proyecto consiste en una solución basada en Inteligencia Artificial para la gestión inteligente de impresoras y predicción automática de cambio de tóner.

El sistema analiza datos históricos de impresión y niveles de cobertura del tóner para identificar impresoras que requieren mantenimiento o reemplazo de consumibles.

Además, genera alertas automáticas, dashboards visuales y reportes exportables en Excel.

---

# Problema que se buscó solucionar

Las empresas suelen tener dificultades para controlar:

* El consumo de tóner
* El desgaste de impresoras
* Los mantenimientos preventivos
* La detección temprana de fallas

Esto genera:

* Altos costos operativos
* Paradas inesperadas
* Mala administración del inventario
* Pérdida de productividad

La solución implementa IA para automatizar estas decisiones.

---

# Tecnologías Utilizadas

## Librerías

* Pandas
* NumPy
* Matplotlib
* Plotly
* Gradio
* OpenPyXL
* XlsxWriter

## Frameworks

* Python
* Gradio Web Interface

---

# Construcción del Dataset

El dataset fue construido a partir de información histórica de impresoras y consumibles.

Se utilizaron variables como:

* Serial de impresora
* Modelo
* Ciudad
* Cantidad de consumibles
* Rendimiento de páginas
* Cobertura de tóner

---

# Cantidad de Datos

El modelo fue entrenado utilizando registros históricos almacenados en archivos Excel.

Cantidad aproximada utilizada:

* Más de 100 registros de impresoras

---

# Modelo de Machine Learning Utilizado

Se implementó un modelo de:

## Regresión Logística

El modelo fue desarrollado manualmente utilizando:

* Función sigmoide
* Descenso de gradiente
* Normalización de datos

---

# ¿Por qué se eligió este modelo?

La regresión logística fue seleccionada porque:

* Es eficiente para clasificación binaria
* Permite predecir probabilidades
* Tiene bajo costo computacional
* Es adecuada para sistemas predictivos simples

El objetivo fue clasificar si una impresora:

* Requiere cambio
* No requiere cambio

---

# Variables Utilizadas

El modelo utilizó:

* Cantidad
* Rendimiento de páginas
* Cobertura de tóner

---

# Métricas Obtenidas

El sistema alcanzó una precisión aproximada superior al 90%.

Se utilizó:

* Loss Function
* Probabilidades predictivas
* Clasificación binaria

---

# Predicciones Generadas

El sistema predice:

* Probabilidad de cambio de tóner
* Estado de la impresora
* Nivel crítico

Ejemplo:

* REQUIERE CAMBIO
* NO REQUIERE CAMBIO
* CRÍTICO

---

# Uso de las Predicciones

Las predicciones permiten:

* Generar alertas automáticas
* Detectar impresoras críticas
* Priorizar mantenimientos
* Reducir fallas operativas

---

# Solución Web Implementada

Se construyó una interfaz web utilizando Gradio.

Funciones principales:

* Visualización del inventario
* Buscador por serial
* Alertas automáticas
* Dashboard interactivo

---

# Frontend y Backend

## Frontend

Desarrollado con:

* Gradio
* Plotly

Incluye:

* Tablas dinámicas
* Buscadores
* Gráficas interactivas

## Backend

Desarrollado en Python:

* Procesamiento de datos
* Entrenamiento IA
* Predicciones automáticas
* Exportación de reportes

---

# Reglas Inteligentes Generadas

El sistema implementa reglas automáticas:

* Si rendimiento > 7000 → posible cambio
* Si cobertura < 6% → alerta crítica
* Si probabilidad > 80% → estado crítico

---

# Funcionamiento General

1. El usuario carga el archivo Excel.
2. El sistema limpia los datos.
3. La IA analiza el estado de cada impresora.
4. Se generan predicciones automáticas.
5. El sistema muestra dashboards y alertas.
6. Se exportan reportes inteligentes.

---

# Objetivo Final

Automatizar el monitoreo de impresoras utilizando Inteligencia Artificial para optimizar el mantenimiento y reducir costos operativos.

---
