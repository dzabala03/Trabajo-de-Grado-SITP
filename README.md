# 👥 SITP-UserProfiling: Caracterización de Usuarios mediante la Encuesta de Transporte y Entornos Urbanos

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Machine Learning](https://img.shields.io/badge/ML-Clustering%20Multidmensional-orange.svg)
![Location](https://img.shields.io/badge/City-Bogot%C3%A1%2C%20Colombia-red.svg)

## 📌 Descripción del Proyecto
Este proyecto de grado se enfoca en la identificación y análisis de **perfiles de usuario** del Sistema Integrado de Transporte Público (SITP) en Bogotá. A través de técnicas de **Ciencia de Datos**, transformamos las respuestas de la *Encuesta de Transporte y Entornos Urbanos* en arquetipos de ciudadanos que permiten entender no solo cómo se mueven, sino por qué lo hacen y cómo perciben su ciudad.

El núcleo del proyecto es pasar de un análisis basado en rutas a uno basado en el **comportamiento y percepción humana**.

## 📊 El Dataset: Dimensiones de Análisis
La base de datos cuenta con variables de alta dimensionalidad que hemos categorizado en:

* **Socio-Demográficas:** Edad, género, nivel educativo y ubicación (Localidad/UPL).
* **Hábitos de Movilidad:** Frecuencia de uso, franjas horarias y motivos de elección (economía, rapidez, necesidad).
* **Satisfacción (Escala Likert 1-5):** Evaluación de 17 factores incluyendo manejo del conductor, aseo, tarifas y frecuencias.
* **Seguridad y Entorno:** Percepción de seguridad dentro del bus, en paraderos y en infraestructuras del barrio (parques, puentes, iluminación).
* **Eventos Críticos:** Registros de accidentes o golpes sufridos en el último año.

## 🛠️ Metodología Técnica
El flujo de trabajo sigue el estándar de un proyecto de Machine Learning:

1.  **Ingeniería de Características:** Tratamiento de datos faltantes y codificación de variables categóricas.
2.  **Análisis de Componentes Principales (PCA):** Reducción de las ~50 variables de satisfacción y entorno para evitar la "maldición de la dimensionalidad".
3.  **Clustering (K-Means / K-Prototypes):** Segmentación de usuarios basada en la similitud de sus respuestas.
4.  **Análisis de Factores de Expansión:** Aplicación de pesos estadísticos para que los resultados sean representativos de la población de Bogotá.



## 🚀 Perfiles Identificados (Ejemplos)
* **El Usuario por Necesidad:** Alta frecuencia, bajos ingresos, percepción crítica de la seguridad.
* **El Usuario por Eficiencia:** Elige el sistema por rapidez o Pico y Placa; valora la cobertura de rutas.
* **El Perfil Vulnerable:** Usuarios con alta tasa de incidentes o percepción de inseguridad en entornos específicos (puentes/paraderos).

## 📂 Estructura del Repositorio
* `notebooks/`: EDA (Análisis Exploratorio) y modelado paso a paso.
* `data/`: Diccionario de variables y guía de acceso al dataset original.
* `src/`: Funciones de procesamiento y visualización de clústeres.
* `results/`: Reportes finales y visualizaciones geográficas.

---
**Desarrollado como proyecto de grado para entender y mejorar la movilidad en Bogotá.**
