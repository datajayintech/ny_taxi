# ny_taxi<br>
Install Postgresql in Docker

    winpty docker run -it \
     -e POSTGRES_USER="root" \
     -e POSTGRES_PASSWORD="root" \
     -e POSTGRES_DB="ny_taxi" \
     -v /c:/Users/Jahmar/2_docker_sql/ny_taxi_postgres_data:/var/lib/postgresql/data \
     -p 5432:5432 \
     postgres:13
     
     
   # Install python in docker 
     
    $ winpty docker run -it python:3.9

