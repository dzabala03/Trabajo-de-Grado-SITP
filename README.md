# 👥 Segmentación de usuarios del Sistema Integrado de Transporte Público (SITP) de Bogotá mediante técnicas de Aprendizaje No Supervisado

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Statistics](https://img.shields.io/badge/Stats-Factor%20Analysis-green.svg)
![Status](https://img.shields.io/badge/Status-Analizando%20Estructura%20Factorial-yellow.svg)

## 📌 Descripción del Proyecto
Este proyecto de grado utiliza la *Encuesta de Transporte y Entornos Urbanos* de Bogotá para perfilar a los usuarios del SITP. A diferencia de análisis descriptivos convencionales, este trabajo implementa un pipeline estadístico riguroso para asegurar que las dimensiones de **satisfacción, seguridad y entorno urbano** sean válidas y confiables antes de proceder a la segmentación.

## 🛠️ Metodología y Avance Técnico
Actualmente, el proyecto se encuentra en la fase de **validación de constructos**, siguiendo este flujo:

1. **Limpieza y Tratamiento de Faltantes:** Procesamiento de datos de la encuesta y manejo de respuestas nulas.
2. **Análisis Factorial Exploratorio (AFE):** Identificación de las variables latentes que explican la percepción del usuario.
3. **Consistencia Interna (Alfa de Cronbach):** Verificación de la fiabilidad de las escalas. (Resultado actual: > 0.70, nivel aceptable).
4. **Análisis Factorial Confirmatorio (AFC):** Validación de la estructura teórica de los factores identificados.


## 📊 Dimensiones Evaluadas
* **Satisfacción del Servicio:** Percepción sobre conductores, aseo, frecuencias y tarifas.
* **Seguridad Percibida:** Evaluación de riesgos dentro del vehículo y en el entorno (paraderos/estaciones).
* **Calidad del Entorno Urbano:** Estado de la infraestructura en el barrio (iluminación, puentes, andenes).

## 🚀 Próximos Pasos
* 🔄 **Clustering Multidimensional:** Una vez validados los factores, se utilizarán los puntajes factoriales para agrupar a los usuarios en perfiles (ej. Usuarios Críticos, Usuarios Satisfechos, Usuarios Vulnerables).
* 📍 **Georreferenciación:** Mapeo de perfiles por Localidad y UPL.

---
**Nota:** Este repositorio documenta el proceso desde la limpieza técnica hasta la interpretación psicométrica del usuario del SITP.
