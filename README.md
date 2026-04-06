# Claude Task Brain 🧠

A persistent memory + adaptive planning system that turns Claude into a long-term intelligent task manager.

## Features
- 🧠 Semantic memory (goals, habits, history)
- 📅 Automatic goal → plan breakdown
- ⚡ Daily execution system
- 🔁 Adaptive planning (adjusts based on progress)
- 🎯 Focus mode (strict, step-by-step guidance)

## Example
User: "I want to score A+ in every exam"

→ Generates full study plan  
→ Tracks progress daily  
→ Adapts based on performance  

## Commands
/focus  
/plan  
/progress  
/reset  

## Tech
- Python
- FAISS / Chroma
- SQLite / PostgreSQL

## Setup
```bash
git clone https://github.com/your-username/claude-task-brain.git
cd claude-task-brain
pip install -r requirements.txt
python app.py
