# django_oobs
 
# Steps:
## Log into github
## Options dropdown (top right user icon) -> Settings
## Developer settings (bottom of left hand menu) -> Personal access tokens
## Generate new token -> Save the token somewhere safe

## Open terminal and navigate to wherever you want the repository, create directory
mkdir django_app
cd django_app

## Clone git repository
git clone https://github.com/tomarmstro/django_oobs.git

## Creating virtual environment
python3 -m venv /venv   %download miniconda3, install, conda create --name OceanObs python=3.8, conda active OceanObs

## Start virtual environment
## python -m venv /venv/Scripts/activate  
# skipped this instead
conda activate OceanObs


## Install required libraries (may need to enter repo directory)
pip install -r /django_oobs/requirements.txt   % pip install -r ./django_oobs/requirements.txt

## Once all requirements are installed, and you're in the repo directory
python manage.py runserver   % cd django_oobs,  python manage.py migrate, python manage.py runserver

## View app in a browser at 127.0.0.1:8000
