# Smart Todo List with AI (Django + OpenAI)

## 🚀 Objective
Build a smart todo list where users can manage tasks with AI features:
- ✅ Task prioritization
- ✅ Deadline suggestions
- ✅ Context-aware enhancements
- ✅ Smart categorization

## 🛠️ Tech Stack
- Backend: Django REST Framework
- AI: OpenAI API (gpt-4)
- Database: Supabase (PostgreSQL)
- Frontend: Next.js with Tailwind CSS (optional)

---

## 📚 Features & APIs

### ✅ GET APIs
- `/api/tasks/` - Fetch all tasks
- `/api/categories/` - Fetch all categories
- `/api/contexts/` - Fetch all context entries

### ✅ POST APIs
- `/api/tasks/` - Create task
- `/api/contexts/` - Add context
- `/api/contexts/suggestions/` - Get AI-powered task suggestions

---

## 🤖 AI Features
- `analyze_context()` — Parses context for urgency
- `prioritize_tasks()` — Scores tasks based on keywords
- `suggest_deadline()` — Suggests deadline based on urgency
- `categorize_task()` — Uses GPT-4 to categorize task
- `enhance_task_description()` — GPT-4 improves task descriptions

---

## 🔐 Environment Variables

Create a `.env` file:
```env
OPENAI_API_KEY=sk-xxxxxx
