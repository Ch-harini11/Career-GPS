# Career-GPS : AI Career Navigator

**One-liner:** Upload a resume → get best-fit roles + a prioritized 4-week roadmap + AI mock-interview feedback.

## Demo & Submission
- Submission PDF: (add Drive link after upload)
- Demo video: (add Drive link after upload)
- GitHub repo: https://github.com/ch-harini11/CareerGPS

## Project overview
CareerGPS analyzes resumes and returns role suggestions, a tailored learning roadmap, and mock interview feedback using OpenAI APIs.

## Tech stack
- Frontend: Plain HTML demo (quick) / React (upgrade)
- Backend: FastAPI (Python)
- OpenAI: GPT for parsing & roadmap, Whisper optional
- Deployment: Vercel (frontend), Render (backend)

## How to run locally
1. Clone repo
2. Backend:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   export OPENAI_API_KEY="sk-..."
   uvicorn app.main:app --reload --port 8000
