# flask_
learn how to make a Rest API using flask, postgres and docker



macOsx env:
brew services start postgresql
docker compose up -d flask_db
docker compose build 

docker compose up flask_app

error: 
 services.flask_app Additional property flask_db is not allowed


docker compose up --build flask_app
