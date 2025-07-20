# 🤖 Asistente Inteligente para Trading con IA Generativa

Este proyecto forma parte de mi ruta de aprendizaje en inteligencia artificial. Se trata del desarrollo de un asistente conversacional inteligente, orientado a tareas de trading, utilizando LLMs (Large Language Models) y herramientas de integración como LangChain.

---

## 🎯 Objetivo

Construir un prototipo de chatbot técnico que sea capaz de:
- Interpretar preguntas relacionadas con indicadores, entradas y estrategias de trading
- Sugerir configuraciones o alertas
- Simular respuestas en base a datos históricos o ejemplos ficticios

---

## 🧰 Tecnologías y Herramientas

- Python 3.10+
- LangChain
- Open Source LLM (Mistral, LLaMA, GPT4All, etc.)
- Gradio (interfaz web)
- FAISS / ChromaDB (vector store opcional)
- Pandas / Streamlit (alternativas de visualización)

---

## 📁 Estructura propuesta

```plaintext
asistente-trading/
├── src/
│   ├── chatbot_engine.py
│   ├── prompt_templates/
│   └── config.yaml
├── interface/
│   └── gradio_ui.py
├── test-data/
│   └── ejemplos-historicos.csv
├── docs/
│   └── casos-de-uso.md
├── README.md
