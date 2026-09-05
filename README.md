# nps-prompt-analysis

Automatización del Análisis Cualitativo de Comentarios NPS mediante Prompt Engineering.

Proyecto Final — Curso *Inteligencia Artificial: Generación de Prompts* (Comisión #96165).
Autor: Cristian Javier Quijada Juárez.

## Contenido

- `nps_prompt_analysis.ipynb` — Notebook principal con introducción, objetivos, metodología, herramientas, implementación, resultados y conclusiones.
- `images/prompt3_resultado.png` — Resultado del prompt texto-imagen (Magnific AI).
- `requirements.txt` — Dependencias del proyecto.
- `.env.example` — Plantilla de variables de entorno (la key real nunca se sube al repo).

## Cómo ejecutar

1. Clona este repositorio.
2. Crea un entorno virtual e instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Copia `.env.example` como `.env` y pega tu propia API key de OpenAI:
   ```
   OPENAI_API_KEY=tu_key_real_aqui
   ```
4. Abre `nps_prompt_analysis.ipynb` en Jupyter o Google Colab y ejecuta las celdas en orden.

## Resumen del proyecto

Automatiza la clasificación y síntesis de comentarios abiertos de NPS (Net Promoter Score) usando técnicas de Fast Prompting sobre el modelo `gpt-5.6-luna` de OpenAI, y complementa el análisis con una pieza de comunicación visual generada con Magnific AI. Ver el detalle completo, incluyendo la comparación entre versiones de prompt y el análisis de costos, dentro de la notebook.
