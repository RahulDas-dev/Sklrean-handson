### Virtual environment creation [ using venv ]

1. Run ```python -m venv --prompt <promt> .venv``` 
2. Check project root directory, it should have ```.venv``` directory
3. Activate virtual environment 
    - For Windows  ```.venv\Scripts\activate.bat```
    - For Linux  ```source .venv/bin/activate```
4. Check new python interpreter path    
    - For Windows  ```where python```
    - For Linux  ```which python```
    - It should point ```${Project_root}/.venv/Scripts/python```
5. install dependency using ```pip install <package_name>```