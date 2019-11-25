# hackernews-gql

Learning Graphql by implementing a graphql server in Django using Graphene and Graphene-django

```
python3.6 -m venv venv
source venv/bin/activate
```
```
pip install django==2.1.4 graphene-django==2.2.0 django-filter==2.0.0 django-graphql-jwt==0.1.5
cd hackernews
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```