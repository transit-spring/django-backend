# transit-spring-backend
Django backend server

# init virtual environment
 `python3 -m venv .venv`

 # activate virtual environment
 `. .venv/bin/activate`

 # start postgres in docker
 This compose file assumes you have a folder named `/var/lib/postgresql/data/` in your host directory.
 Make sure that you have docker running and that port 5432 is free.
  `docker compose up -d`