# 🧠 Therapist Ava – A Memory-Based AI Therapy Bot

Welcome to **Therapist Ava**, your warm and empathetic AI therapy companion. This chatbot simulates a cognitive behavioral therapist with a consistent personality and session memory to provide comforting and context-aware responses.

---

## 🌟 Features

- **Persona-Based Bot:**
  - **Name**: Ava
  - **Age**: 38
  - **Style**: Empathetic, warm, occasionally uses metaphors
  - **Experience**: 10+ years in Cognitive Behavioral Therapy (CBT)

- **Memory Handling:**
  - Remembers the last **6 exchanges** (user + Ava)
  - Maintains consistent context during a session
  - Memory is reset with the `restart` command

- **Mood Tracker:**
  - Ava starts the session by asking your mood (1–10 scale)

- **Commands:**
  - `quit` → Exit the session
  - `restart` → Clear memory and begin a new session

---

## 🛠 Requirements

- Python 3.8+
- OpenAI SDK (`openai`)
  
Install using:

```bash
pip install openai
