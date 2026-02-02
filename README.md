# KC-LLMM

# Fine-tuning de un modelo LLM para la generación de ejercicios de inglés (B1)

## Descripción del proyecto

Este proyecto explora el uso de un modelo de lenguaje de gran tamaño, concretamente Mistral 7B Instruct, fine-tuneado mediante un dataset artificial, con el objetivo de generar materiales didácticos de inglés de nivel B1 orientados a alumnado de Formación Profesional.

El trabajo analiza hasta qué punto un modelo fine-tuneado es capaz de generar ejercicios útiles y aplicables en un contexto educativo real, como ejercicios de word formation, actividades de gramática, ejercicios de contraste gramatical y actividades de reading comprehension.

## Objetivos

Los objetivos principales del proyecto son:

- Comprender el proceso completo de fine-tuning de un modelo LLM.
- Diseñar un dataset artificial orientado a tareas educativas.
- Evaluar la capacidad del modelo para generar ejercicios lingüísticos estructurados.
- Analizar las limitaciones del prompting en tareas con una estructura cerrada.
- Valorar la viabilidad del uso de modelos gratuitos en contextos educativos.

## Tecnologías utilizadas

- Python  
- Hugging Face Transformers  
- PEFT (LoRA / QLoRA)  
- BitsAndBytes (cuantización en 4 bits)  
- Google Colab  
- Mistral 7B Instruct  

## Estructura del repositorio

```text
KC-LLMS/
├── .git/
├── dataset.jsonl
├── Entrega.ipynb
├── presentación.pptx
└── README.md
