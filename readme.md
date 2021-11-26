# trying holoviz...

```bash
pyenv virtualenv 3.8.11 try_holoviz
pyenv local try_holoviz
pip install hvplot
pip install --upgrade pip
pip install jupyter
pip freeze > requirements.txt
jupyter notebook
```
