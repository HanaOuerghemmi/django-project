# Doclist

``
1st step :pip list
pip freeze > reuirement.txt
django-admin startproject doclist
``
````
2sd step
creer l app 
python manage.py startapp tasks
````
````
python3 manage.py runserver
python3 manage.py migrate
python3 manage.py makemigrations
````
ad the name of the app in file setting 
add model in file modeles class Collction exemple
def index html in the file views
# Modeles
- collection
  - name
  - slug
- Task
  - description
  - collection (ForeignKey)
  - 
# Fonctionalités

[x] add collection   
[] Delete collection    
[] update / Rename collection   
[x] empecher l ajout dune collection en doublon  
[] add task (relié a un collection)     
[] delete task  
[] afficher task of collection  