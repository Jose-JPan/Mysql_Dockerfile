# First step | Primeiro Passo
$ docker build -t mysql_db .

# Second step | Segundo Passo
$ docker run mysql_db

@ In another terminal | Em outro terminal 
# Third step | Terceiro Passo
$ docker exec -it [CONTAINER_ID] /bin/bash

# Forth step | Quarto Passo
/# mysql -proot

