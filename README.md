# ✍️ CORRECTOR ORTOGRÁFICO EN PYTHON: APLICANDO TÉCNICAS DE NLP

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)  
[![NLTK](https://img.shields.io/badge/NLTK-283990?style=flat&logo=python&logoColor=white)](https://www.nltk.org/)

Este proyecto simula la **creación de un corrector ortográfico** utilizando **Procesamiento de Lenguaje Natural (NLP)** y lógica computacional en Python. El objetivo es construir un "traductor/transmisor" que sea capaz de interpretar una palabra mal escrita por un humano y devolver la palabra correctamente escrita.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Fundamentos de NLP
- **Definición de NLP:** Se establece que NLP es la ciencia que combina **Lingüística + Computación + Inteligencia Artificial** para simular un traductor, permitiendo que las máquinas interpreten el lenguaje humano natural.
- **Caso de Uso:** La simulación se basa en mejorar la funcionalidad de un buscador (ej. una plataforma que no corrige errores ortográficos) para que pueda sugerir la palabra correcta aun cuando el usuario la escriba mal.

### 2️⃣ Metodología de Corrección
- **Manejo de Vocabulario:** El modelo se entrena en un **corpus de texto** para generar un diccionario de palabras conocidas y sus frecuencias.
- **Distancia de Edición (Inferido):** El proceso implica generar posibles correcciones para una palabra errónea y medir qué tan cerca está cada corrección de una palabra conocida del diccionario.
- **Cálculo de Frecuencia:** La corrección final se selecciona no solo por la cercanía, sino también por la **frecuencia de uso** de la palabra en el lenguaje.

### 3️⃣ Evaluación y Mejora del Modelo
- **Métrica de Acertividad:** Se calcula la *accuracity* (acertividad) del modelo midiendo cuántas de sus correcciones coinciden con la corrección real esperada.
- **Análisis de Capacidad Máxima:** Se determina la **máxima acertividad posible (88%)** con los datos actuales.
- **Identificación de Brechas:** Se cuantifica el porcentaje de mejora potencial (**aproximadamente 22.9%**), destacando que se pueden incluir más escenarios para optimizar el modelo (ej. considerar palabras con múltiples errores como LÓGGGICA).

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Python**     | Lenguaje base para la implementación de la lógica del corrector|
| **NumPy**      | Operaciones numéricas para la manipulación y conteo de datos (inferido) |
| **NLTK (Natural Language Toolkit)** | (Uso fundamental inferido) Librería para el preprocesamiento de texto, tokenización y manejo del vocabulario |

---

## 🎯 Objetivo del Proyecto
Crear un **corrector ortográfico funcional** que demuestre los principios básicos de NLP. El proyecto busca mostrar cómo se pueden aplicar la lingüística y la probabilidad para interpretar el lenguaje natural y **mejorar la experiencia del usuario** en sistemas de búsqueda y entrada de texto.

---

## 📈 Resultados Clave
- El modelo inicial logra una **acertividad de aproximadamente 65.71%**.
- Se establece una meta de mejora teórica de hasta **88%** al incluir más escenarios de error y mejorar la lógica de corrección.
- La principal conclusión es la necesidad de **seguir incluyendo escenarios** (como errores con 3 letras repetidas) para alcanzar el potencial máximo de corrección del modelo.

