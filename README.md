
# 🤖 Agente Asistente de Perfil — RAG Deployment with Dify & DeepSeek
[English Version Below]

Un Agente de Inteligencia Artificial avanzado configurado como Asistente de Perfil Profesional.
Utiliza una arquitectura RAG (Retrieval-Augmented Generation) para responder consultas de forma precisa basándose en documentación específica (CV, portfolio, experiencia y skills), eliminando alucinaciones y garantizando respuestas alineadas a un rol corporativo.

---

## 🏗️ Arquitectura del Sistema
* **Orquestador de Agentes:** [Dify.ai](https://dify.ai/) (Plataforma LLMOps avanzada para la gestión de prompts, variables de contexto, memoria conversacional y pipelines de RAG).
* **Motor de Inferencia (LLM):** DeepSeek (DeepSeek-R1 / DeepSeek-V3), optimizado para razonamiento lógico, extracción de entidades y alta eficiencia en costos/rendimiento.
* **Estrategia RAG (Base de Conocimiento):** Indexación de documentos semiestructurados dentro del motor de vectores de Dify, utilizando segmentación (*chunking*) inteligente y embeddings para búsquedas semánticas de alta precisión.

## 📌 Características Clave
* **Memoria de Contexto:** Gestión de hilos de conversación para mantener el flujo del diálogo durante entrevistas simuladas o consultas de clientes.
* **Filtro de Alucinaciones:** El agente está restringido mediante *system prompts* estrictos para responder únicamente utilizando la base de conocimiento inyectada.
* **Personalidad Adaptativa:** Configurado para interactuar con un tono profesional, técnico y resolutivo, ideal para interactuar con reclutadores o potenciales clientes freelance.

---

# 🇺🇸 English Version

An advanced AI Agent configured as a Professional Profile Assistant. It leverages a RAG (Retrieval-Augmented Generation) architecture to accurately answer queries based on specific corporate documentation (CV, portfolio, background, and expert skills), effectively mitigating LLM hallucinations.

---

## 🏗️ System Architecture
* **Agent Orchestrator:** Dify.ai (Advanced LLMOps platform managing prompt engineering, context variables, conversational memory, and RAG pipelines).
* **Inference Engine (LLM):** DeepSeek, selected for its elite logical reasoning, entity extraction, and cost-to-performance efficiency.
* **RAG Strategy (Knowledge Base):** Chunking and indexing of unstructured personal/professional data within Dify's native vector suite for high-precision semantic retrieval.

## 🗺️ Roadmap & Next Steps / Próximos Pasos
1. **API Gateway Integration:** Conectar el endpoint HTTP de Dify con una interfaz web personalizada o canales de mensajería (WhatsApp/Telegram).
2. **Advanced Analytics:** Implementar el monitoreo de logs de conversación en Dify para evaluar la precisión del RAG y optimizar los hiperparámetros de recuperación (Top-K, Score Threshold).
