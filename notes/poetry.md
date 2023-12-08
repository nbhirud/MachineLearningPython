
# Getting started with Poetry
## installing 
```
pip install poetry
```

## Add to path
Adding `C:\Users\<USERNAME>\AppData\Roaming\Python\Python312\Scripts` to PATH makes poetry available directly on terminal

## Set virtual env to be created within project dir
```
poetry config virtualenvs.in-project true
```

## Watch this and get started:
https://youtu.be/0f3moPe_bhk?si=zgxefKXvDj3PF1V-

## Initialization
go to project folder and run following

```
# This step is interactive and it created a pyproject.toml based on user inputs
poetry init  

# This step creates the virtual environment based on init step
poetry install
```

# How to see poetry info?
```
poetry env info
```

# Run programs inside this virtual env
```
poetry shell
```
