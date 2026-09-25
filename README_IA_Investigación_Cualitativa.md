🗺️ Metodología de Mapeo Semántico y Geográfico (v6.1)
Este repositorio documenta el flujo de trabajo estandarizado para transformar información cualitativa (transcripciones de entrevistas) en datos espaciales (capas SIG) mediante el uso de Inteligencia Artificial y análisis semántico.

El proyecto se enfoca en el análisis de movilidad, seguridad vial y apropiación del espacio público en diversas zonas de Bogotá y Sumapaz.

📂 Contenido del Repositorio
En la carpeta docs/ encontrarás los dos pilares de esta metodología:

1. 📜 Prompt Canónico (Instrucciones para IA)
Es el "cerebro" del procesamiento. Contiene la ingeniería de prompt diseñada para que Modelos de Lenguaje (LLMs como ChatGPT o Gemini) actúen como asistentes de investigación.

Función: Extrae referencias espaciales, categoriza fenómenos (seguridad, conflictos, cuidado) y estructura la data en una tabla normalizada.
Salida: Genera registros listos para ser geocodificados.
2. 📘 SOP (Procedimiento Operativo Estándar)
Es el manual de reglas para el analista humano. Asegura la consistencia y calidad de los datos.

Define: Criterios de exclusión/inclusión, manejo de ambigüedades geográficas y estandarización de categorías (Ejes y Subejes).
Uso: Sirve de guía para la revisión y validación de los resultados arrojados por la IA.
🚀 Flujo de Trabajo
La metodología sigue este pipeline:

Input: Transcripciones de entrevistas (estructuradas/semiestructuradas).
Procesamiento: Se aplica el Prompt Canónico para detectar lugares y fenómenos.
Estructuración: Se clasifican los hallazgos en Ejes (A: Seguridad Vial, B: Uso, C: Apropiación) y Enfoques Transversales.
Spatial Join Lógico: Se asigna cada hallazgo a una IZ (Zona de Estudio) específica (ej. Bosa Nova, Sierra Morena, Sumapaz).
Output: Una matriz tabular lista para ser convertida en geometría (Puntos/Líneas) en software SIG (ArcGIS Pro / QGIS).
📍 Zonas de Estudio
El alcance actual cubre 12 zonas estratégicas, incluyendo:

Urbano: Bosa, Ciudad Bolívar, Suba, Kennedy, Fontibón, Chapinero, Puente Aranda.
Rural: Sumapaz (Centro poblado Nazareth).
Este repositorio sirve como muestra de metodologías mixtas (Cuali-Cuanti) aplicadas a estudios territoriales.
