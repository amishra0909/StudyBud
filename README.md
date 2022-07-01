# StudyBud

### Steps to install and run

--> Clone the repository using the command below :
```bash
git clone https://github.com/amishra0909/StudyBud

```

--> Move into the directory where we have the project files : 
```bash
cd StudyBud

```

--> Create a virtual environment :
```bash
# Let's install virtualenv first
pip install virtualenvwrapper

# Change the $WORKON_PATH env variable to place where you want to keep all virtualenvs

# Then we create our virtual environment
mkvirtualenv envname

```

--> Activate the virtual environment :
```bash
workon envname

```

--> Install Django :
```bash
pip install django

```

--> Change directory and start django server :
```bash
cd studybud
python manage.py runserver
```
