Launch the server with

`docker-compose up`

Then visit the site at http://localhost:8080

Launch the seeder with:

`docker exec -ti [web_container_name] python manage.py seed --mode=refresh`


Launch one crawler:

`docker exec -ti [web_container_name] python crawl seed --name=crawler_name`

