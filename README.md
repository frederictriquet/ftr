# docker

`docker-compose exec <container> bash`

`docker system prune --all --volumes`

`docker system df`

`docker builder prune`
`docker volume prune`
`docker volume ls`

`docker container ls -a`

`docker container rm [id]`

`docker container ls -aq` --> lister juste les ID

`docker container rm $(docker container ls –aq)` --> supprimer tous les conteneurs arrêtés

`docker image ls`

`docker image rm [id]`

# git

`git stash pop == git stash apply && git stash drop`

`git checkout 'master@{1979-02-26 18:30:00}'` --> checkout à une date

# php
`$e = new \Exception; var_dump($e->getTraceAsString());die();`
