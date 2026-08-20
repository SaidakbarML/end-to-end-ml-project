# End-to-End ML Project

A complete, deployable machine learning project following a standard production-style ML pipeline structure.

## Why this exists
Practice building an ML project the way it would be structured for real deployment: modular source code, an artifacts folder, a web app, and a defined package setup — not just a notebook.

## Tech stack
Python, Flask-style app (`app.py`, `templates/`), CatBoost

## How to run
1. `pip install -r requirements.txt` (or `python setup.py install`)
2. `python app.py` to launch the web app
3. `notebook/` contains the original experimentation notebooks; `src/` contains the production-structured pipeline code; `artifacts/` holds trained model outputs
