# Environment Setup

## Virtual Environment
**Location:** `C:\venvs\alberta_eda`

Kept outside OneDrive to avoid path length issues on Windows and prevent OneDrive from syncing venv files.

## Activate (Windows)
```bash
C:\venvs\alberta_eda\Scripts\activate
```

## Install dependencies
```bash
pip install -r requirements.txt
```

## Why not inside the project folder?
Windows has a 260-character MAX_PATH limit. OneDrive paths are already long.
Jupyter's internal extensions push paths well past that limit during install.
Rule going forward: **all venvs live in `C:\venvs\<project_name>`**.
