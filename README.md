## TOV Copywriter

### Setup
1. Create and activate a virtual environment
   - macOS/Linux:
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```
   - Windows (PowerShell):
```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```
2. Create `.env` with your OpenAI key:
```env
OPENAI_API_KEY=sk-...
# Optional: override model
OPENAI_MODEL=gpt-4o-mini
```

### Run
```bash
streamlit run app.py
```

### Notes
- Data persists to `data/app_state.json`.
- Use the sidebar to manage projects and navigate to Editor, History, and Tone of Voice Admin.
