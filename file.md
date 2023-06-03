docker exec -it a7963496447a bash

docker cp wine.data a7963496447a:/home/jovyan/wine.data

docker build . -t my_notebook

docker run -v /Users/refresh/Desktop/docker:/home/jovyan/ -it --rm -p my_notebook