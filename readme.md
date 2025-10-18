### configuration env

## start env virtual
python -m venv .venv

# If you do it in bash, then.
source .venv/Scripts/activate

# If you do it in PowerShell, then.
.venv\Scripts\activate

# instalacion de dependencias.
pip install --upgrade pip
pip install "opencv-python>=4.8,<5.0" "numpy>=1.24,<3.0" "matplotlib>=3.7,<3.10"

