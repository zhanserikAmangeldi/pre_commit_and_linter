# Linter and Pre-commit in use
Example of using Linters and Pre-commit with python.

# Getting Started
Make git clone and let's start! (all commands msut executed in root dir)

### What we need?
We need to install two pyton libraries, flake8 and pre-commit.
```
pip install flake8 pre-commit
```

### What we should do?
First we must install configs to pre-commit.
```
pre-commit install --hook-type pre-commit --hook-type commit-msg
```
After that pre-commit hooks will work.

# Ex:
1. I have a python code with lenth of line more than 80.
<img src="https://github.com/user-attachments/assets/b1015b92-8c9d-4fbc-a19f-e61798b33041" width="800px">

2. There you can see the flake8 configuration file where I write that max lenth of line equal to 80.
<img src="https://github.com/user-attachments/assets/0b3e2abc-5e06-41c4-bd6b-27a4e601b886" width="800px">

3. And there you can see how pre-commit prevent commiting.
<img src="https://github.com/user-attachments/assets/24a039dd-0b31-41de-b338-a6dc47d974db" width="800px">

Additionally, there you can see how pre-commit prevent commitin becase message of commit doesn't fit to format.
<img src="https://github.com/user-attachments/assets/b120507e-a4a3-43d2-851b-1b793d40dc8f" width="800px">
