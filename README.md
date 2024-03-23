# Jak sprawdzić wersję Python:

```
python --version
```

# Jak utworzyć wirtualne środowisko dla Python: 

```
python -m venv tutorial-env
```

# Jak uruchomić wirtualne środowisko dla Python na Windows:

```
tutorial-env\Scripts\activate
```

# Jak zainstalować wymagane biblioteki: 

```
make install
```

w przypadku problemów z make, instalacje środowiska można wykonać z:

```
pip install –r requirements.txt
```


# Jak zamknąć wirtualne środowisko dla Python na Windows:

```
deactivate
```

# Jak uruchomić aplikacje flask:

```
make run 
```

w przypadku problemów z make:

```
flask run
```

# Jak dodać pylint:

```
make lin
```

w przypadku problemów z make:
```
pip install pylint
```

# Jak uruchomić pylint:

z cmd dla Windows:
```
python -m pylint app.py
```