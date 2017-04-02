# docker_pinry
This is just a leanring exercies for me. Trying pinry via docker ubuntu.

I would advise againt cloning and using.


## usage

docker run -p 8000:8000 -it mikedata/docker_pinry

cd to pinry

python manage.pt migrate

python manage.py runserver 0.0.0.0:8000
