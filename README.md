Small, personal ML practice repo. The project revolves around one main notebook and the small CSV datasets included — it's intended for learning and experimentation, not production.

What’s in the repo
- main.ipynb — the single runnable notebook that performs EDA, light preprocessing, simple model training and quick evaluation (keeps a learning / exploratory style).
- train.csv, test.csv — datasets used by the notebook.
- requirements.txt — minimal Python dependencies to run the notebook.

Quick start
1. Create an environment and install dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate    # macOS / Linux
   .venv\Scripts\Activate.ps1   # Windows PowerShell
   pip install -r requirements.txt
   ```
