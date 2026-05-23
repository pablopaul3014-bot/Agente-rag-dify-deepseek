markdown
# Agente de IA Autónomo con Arquitectura RAG - Perfil Profesional

Este proyecto consiste en el diseño, desarrollo e implementación de un agente de inteligencia artificial autónomo capaz de interactuar con usuarios y responder consultas técnicas sobre un perfil profesional de manera precisa y sin alucinaciones, utilizando una arquitectura de generación aumentada por recuperación (RAG).

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Orquestador de IA:** Dify.ai (Versión Cloud) para la gestión del flujo de trabajo, prompts y carga de conocimiento.
* **Modelo Fundacional:** DeepSeek-V3 (LLM avanzado de razonamiento y procesamiento de lenguaje natural).
* **Infraestructura de Modelos:** SiliconFlow API para la integración y ejecución eficiente del modelo de lenguaje.
* **Base de Conocimiento (RAG):** Indexación automatizada y segmentación de documentos en PDF/Word para consulta en tiempo real.

## 🧠 Características Técnicas del Sistema
* **Ingeniería de Prompts Avanzada:** Implementación de directivas estrictas de comportamiento (*System Prompts*) y delimitadores de contexto para mitigar alucinaciones y delimitar el alcance del conocimiento.
* **Arquitectura RAG Eficiente:** Extracción precisa de datos estructurados y desestructurados (fechas, instituciones, aptitudes técnicas) directamente desde la base de conocimientos adjunta.

## 🚀 Cómo replicar este agente
1. Descarga el archivo `AsistentePerfil.yml` de este repositorio [2].
2. Inicia sesión en tu cuenta de Dify.ai.
3. En el panel principal, selecciona **"Importar archivo DSL"** y sube el archivo `.yml`.
4. Configura tus credenciales de SiliconFlow para el modelo `deepseek-ai/DeepSeek-V3` ¡y listo!
