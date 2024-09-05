# examen
# Créer et activer un environnement virtuel
python -m venv env
source env/bin/activate  
.\env\Scripts\activate  

# Installer Django et autres dépendances
pip install django
pip install -r requirements.txt



# Accéder au répertoire du projet


# Appliquer les migrations
python manage.py migrate

# Créer un superutilisateur
python manage.py createsuperuser

# Lancer le serveur de développement
python manage.py runserver