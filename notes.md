1 - install python
2 - pip3 install -U pip
3 - pip3 install rasa
4 - python -m rasa init

## RAZA
# lancer le chat dans le terminal
python -m rasa shell 

# train le chat apres modif 
python -m rasa train 

# lancer le server
python -m rasa run --enable-api


## Python Django
pip install django
django-admin startproject chatbotai // créer un projet nommé chatbotai
python manage.py runserver   // lancer le serveur 
python manage.py startapp rasa // créer un module nommé rasa
python manage.py makemigrations // mettre à jour les entités
python manage.py migrate // Mettre à jour la bd
python manage.py createsuperuser // créer un user admin

// accès admin django
http://127.0.0.1:8000/admin/

protobuf==4.21.12
