# CareerForge 🔥
AI-powered résumé analyzer + enhancer (FastAPI).  
Upload a PDF CV + paste a job description → get:
- Skill match score
- Found/Missing skills
- Improved bullet points with strong action verbs
- Short summary + cover letter draft
- Downloadable markdown pack

https://github.com/eyaa5/careerforge

## ✨ Demo (local)
```bash
# 1) Create environment (optional)
python -m venv .venv
# Windows:
.venv\Scripts\activate

# 2) Install deps
pip install -r engine/requirements.txt  # or: pip install fastapi uvicorn pypdf

# 3) Run API
uvicorn api.main:app --reload

# 4) Open UI
# http://127.0.0.1:8000
