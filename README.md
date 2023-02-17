# Virtual-Environment-Cheat-Sheet


# Virtual Environment

# On CMD

- pip list - list of package installed globally
- python -m venv <project_name> - create a Virtual Environment
- <project_name>\Scripts\activate.bat - activate venv
- pip freeze - same with pip list but it will give ask the correct form in txt file
- deactivate - deactivate the venv
- rmdir project_env /s - delete venv project

# Better Process

- mkdir my_project - create project folder
- python -m venv venv - create virtual environment inside my_project
- my_project\venv\Scripts\activate.bat - activate venv
- pip install -r requirements.txt - install all the packages on the requirements.txt
- deactivate - deactivate venv
- rmdir venv /s - delete venv inside my_project folder

# Optional

- python -m venv venv - -system-site-packages - this will install all packages global in your project
- Note: this is when your inside my_project folder

# Requirements

- pip install -r requirements.txt - install all packages required

# Fastest Way

- `py -3 -m venv venv`
- `venv\Scripts\activate`
