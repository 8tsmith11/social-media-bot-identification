# Setup

Create a virtual environment and install dependencies from `pyproject.toml`.

```sh
# Windows (PowerShell)
py -3 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -e .

# macOS / Linux (bash)
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -e .
