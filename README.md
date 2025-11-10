# Human-semantic-graph
# Смысловой Граф Человека (Human Semantic Graph)

> «Понимание — это не описание, а оперирование структурой смысла.»

## 🌍 Цель
Создать открытую систему, которая:
- извлекает структуру смысла из естественного языка,
- хранит её в виде динамического, иерархического графа,
- отвечает на вопросы через рассуждение, а не статистику,
- в перспективе — позволяет сравнивать культурные онтологии (русская, китайская, западная и др.).

## 🧪 Минимальная версия (MVP)
- Ввод: текст на русском языке (например: «Почему небо синее?»)
- Система строит граф связей:  
  `небо → цвет ← рассеяние_Рэлея ← длина_волны(синяя)`
- Ответ генерируется на основе структуры, а не шаблона.
- Хранение: графовая база данных (Neo4j).
- Модель: открытая LLM (Gemma, Phi-3), дообученная на извлечении смысла.

## 🛠️ Технологии
- Python
- Neo4j (графовая БД)
- Hugging Face Transformers
- Gradio (простой веб-интерфейс)
- Запуск: бесплатно на Hugging Face Spaces

## 🤝 Ищу соавтора!
Я — автор идеи, философ и архитектор смысла.  
Ищу разработчика, который поможет реализовать MVP.  
Готов обсуждать, объяснять, участвовать в дизайне — но не писать код.

Если вы верите, что ИИ должен **понимать**, а не только угадывать — пишите!

---

# Human Semantic Graph

> "Understanding is not description, but operation on the structure of meaning."

## 🌍 Vision
Build an open system that:
- Extracts semantic structure from natural language,
- Stores it as a dynamic, hierarchical knowledge graph,
- Answers questions through reasoning, not statistical prediction,
- Eventually enables cross-cultural ontology comparison (Russian, Chinese, Western, etc.).

## 🧪 MVP
- Input: Russian text (e.g., "Why is the sky blue?")
- System builds a graph:  
  `sky → color ← Rayleigh_scattering ← wavelength(blue)`
- Response is generated from structure, not templates.
- Storage: Neo4j graph database.
- Model: fine-tuned open LLM (Gemma, Phi-3).

## 🛠️ Stack
- Python
- Neo4j
- Hugging Face Transformers
- Gradio (web UI)
- Free hosting on Hugging Face Spaces

## 🤝 Looking for a co-founder!
I’m the idea author, philosopher, and semantic architect.  
Looking for a developer to build the MVP.  
I’ll explain, discuss, and co-design — but won’t code.

If you believe AI should **understand**, not just predict — let’s talk!
