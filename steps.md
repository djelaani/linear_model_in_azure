## Install dependencies

```
pip install Flask
pip install sklearn
```

## Create app.py
You create simple linear regression app that tells you what salary you'll get for a given years of experience

## Create templates
index.html
prediction.html

## Install new dependencies
```
pip install flask_sqlalchemy
pip install flask_Script
pip install flask_Migrate
```

## In app.py

```
from flask_sqlalchemy import SQLAlchemy
```

```
app.config.from_object("config.DevelopmentConfig")
app.config['SQLALCHEMY_TRACK_MODIFICATIONS'] = False
db = SQLAlchemy(app)
```





#### MISE EN PROD #####

Go sur Azure
- Créer une base Postgresql
- Setup PostgresqlServer avec les credentials suivant :
login : antoinekrajnc01
pw : Q+J~5Y;UdxD=


- Mettre en place les variables d'environnements
- Pusher sur Github
- Créer une Web App + Postgresql sur Azure
- Enlever les dossiers liés à Virtualenv
