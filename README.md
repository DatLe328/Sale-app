# Sale-app
The mobile phone store software has basic functions.

# Requirements
- MySQL
- Python
# Installation
- Change MySQL's password and schema's name in \_\_init__.py file.
- Create virtualenv.
- Run dao.py file to init database
# Run app in terminal:
## Windows
```shell
# Activate virtual environment
.\.venv\Scripts\activate
# Assign PYTHONPATH 
$env:PYTHONPATH = (Get-Location).Path
```
## Linux
```bash
# Activate virtual environment
source .venv/bin/activate
# Assign PYTHONPATH 
export PYTHONPATH=$(pwd)
```