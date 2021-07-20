# django-personal-portfolio

## Clone GitHub Repository's
```bash
git clone https://github.com/keyinora/django-personal-portfolio.git
```
## Create Virutal Environment Steps
Command: mkvirtualenv --python=/usr/bin/python3.9 [environment name]

```bash
mkvirtualenv --python=/usr/bin/python3.9 portfolioenv
```
## Start a previously created Virutal Environment

Command: virutalenv [environment name]
```bash
virutalenv portfolioenv
```

## OR Python Everywhere Bash Terminal

Command: workon [environment name]
```bash
workon portfolioenv
```

## To Stop a Virutal Environment
```bash
deactivate
```

## setting up Static files on Python Anywhere

```bash
python manage.py collectstatic
```

## show full file path in Bash
```bash
pwd
```

## git commands
```bash
#removes all cached files, use if your still seing files that should be ignored by your .gitignore
git rm -r --cached .
#full up with the following command
git add .
#commit your changes
git commit -m "My Commit comments"
```
## Create a requirement.txt file

This file will outline all pip packages you require to run your project.

Please note that if you did not run a virutal environment, it will show all packages on your system.
```bash
pip freeze > requirements.txt

#on Production server, run below command to install packages on your production server
pip install -r requirements.txt
```