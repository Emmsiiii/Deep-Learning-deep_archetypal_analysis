# Intro
all code is in `Project_final.ipynb`

# Environment Setup
- From the project root, create a virtual environment: `python3 -m venv .venv`
- Activate it: `source .venv/bin/activate` (bash/zsh), `source .venv/bin/activate.fish` (fish), or `.venv\Scripts\Activate.ps1` (Windows PowerShell)
- Upgrade the installer to avoid dependency glitches: `pip install --upgrade pip`
- Install project dependencies: `pip install -r requirements.txt`
- If you hit `ModuleNotFoundError` for a package not listed in `requirements.txt`, install it (`pip install <package>`), then pin it so everyone stays in sync: `pip freeze > requirements.txt`
- When you are done coding, deactivate with `deactivate` or just close the shell
