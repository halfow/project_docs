# Documentation test project

## Build
```powershell
# Setup virtual environment
python3 -m venv .venv --prompt "docs"

# Activate virtual environment
.venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Build documentation
cd docs
make.bat clean
make.bat html
```
