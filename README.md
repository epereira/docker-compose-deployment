This is a WildCodeSchool Docker Challenge.

Docker compose used with 3 containers

Docker deployment for dev :
- 1 container server with Nest connected to MongoDB on container number 2
- 1 container with MongoDB
- 1 container client with react and hot relaod activated.

Clone this repo and deploy it with this commande line : 
docker compose -f docker-compose.dev.yml up --build
