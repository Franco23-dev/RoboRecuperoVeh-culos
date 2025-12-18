# 🚗 Robos y Recupero de Vehículos en Argentina (2024)

Análisis exploratorio y visual de los registros oficiales de robos y hurtos de vehículos en Argentina durante el año 2024, utilizando Power BI como herramienta principal.

---

## 🎯 Objetivo del Proyecto

Este proyecto surge como una práctica de análisis de datos con el fin de:

- Fortalecer habilidades en limpieza, transformación y modelado de datos  
- Aplicar métricas e indicadores relevantes  
- Construir dashboards claros y funcionales  
- Documentar el proceso como parte de un portafolio profesional  

---

## 📊 Fuente de Datos

Los datos provienen de una **base pública del Gobierno de Argentina**, que contiene registros de denuncias por robos y hurtos de vehículos a nivel nacional durante el año 2024.

Para preservar la integridad de la información:

- Se trabajó sobre una **copia del dataset**
- El archivo original no fue modificado

---

## 🧹 Limpieza y Preparación de los Datos

Antes del análisis, se realizaron tareas de depuración y transformación:

- Eliminación de registros nulos o incompletos  
- Conversión de columnas a los tipos de datos correspondientes  
- Eliminación de campos sin valor analítico ni permisos de uso:
  - `titular_domicilio_provincia_id`
  - `titular_pais_nacimiento_id`

Estas columnas no aportaban información relevante ni relación directa con el análisis planteado.

---

## ❓ Preguntas de Negocio

El análisis se orientó a responder las siguientes preguntas clave:

- ¿Cuántos registros totales se denunciaron durante 2024?
- ¿Cuántos vehículos fueron denunciados por provincia?
- ¿En qué período del año se registraron más denuncias?
- ¿Cuál es el promedio de denuncias realizadas?
- ¿Qué tipo de vehículos fueron afectados?
  - Privado
  - Público
  - Oficial
  - Sin declarar
- ¿Cuál es el origen de los vehículos?
  - Nacional
  - Importado
  - Protocolo 21

---

## 📈 Visualización y Análisis

Con las respuestas obtenidas, se desarrolló un **dashboard en Power BI**, enfocado en:

- Claridad visual  
- Lectura rápida de indicadores  
- Análisis exploratorio  
- Identificación de patrones temporales y geográficos  

El tablero permite interactuar con los datos y profundizar el análisis de manera dinámica.

---

## 🔗 Acceso al Dashboard Interactivo

👉 **[Ver informe interactivo en Power BI](https://app.powerbi.com/view?r=eyJrIjoiNGRjMmIxM2QtMGYxZS00NWZjLWFjYzMtMDI5MmExOGIwYzBiIiwidCI6IjUzNTIzNTc0LTAxMDYtNDRiYy1hZDNlLWY4ODg3ZWQ2YzJkMSIsImMiOjR9&embedImagePlaceholder=true)**

---

## 🛠️ Herramientas Utilizadas

- Power BI  
- Power Query  
- DAX (medidas básicas)

---

## 🧠 Aprendizajes

- Trabajo con datos públicos reales  
- Limpieza de datasets con información sensible  
- Enfoque analítico basado en preguntas de negocio  
- Desarrollo de dashboards claros y funcionales  

---

## 🙋‍♂️ Autor

Proyecto realizado por **Franco Vera**
