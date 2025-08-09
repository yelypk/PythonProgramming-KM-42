# PythonProgramming-KM-42

Educational repository for the discipline "Programming in Python" (KPI, FPM, group KM-42).
Tasks are designed as independent modules; Qt Widgets (PyQt5 / PySide6) is used for the graphical interface.

## Repository composition

- `modul8/` — source code of solutions for module 8 (GUI on Qt Widgets, auxiliary modules and resources).
- `modul8.zip` — archive with the same sources in case of convenient downloading in full.
- `posheliuk_yelyzaveta_KM-42.txt` — identifier/information about the student and group.
- `KM-42.docx` — manual/task of the teacher for the group.

> Note: the source code is up-to-date in the `modul8/` folder. The `modul8.zip` archive is stored for control of the task version.

## Quick Start

### 1) Requirements
- Python 3.10+ (3.11 recommended)
- One of the Qt bindings:
- **PyQt5**: `pip install pyqt5`
- or **PySide6**: `pip install pyside6`

### 2) Installation
```bash
# Clone repository
git clone https://github.com/yelypk/PythonProgramming-KM-42.git
cd PythonProgramming-KM-42

# (optional) create a virtual environment
python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/macOS:
source .venv/bin/activate

# Install dependencies
pip install -U pip
pip install pyqt5 
