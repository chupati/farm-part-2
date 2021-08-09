# farm-part-2
FARM Stack with Docker Compose - Part 2

Once you copy the repo you can type the following command assuming you have Docker Compose installed on your machine.

docker-compose up

You may notice that the mongo-express service may fail a few times. The service is waiting for the MongoDB service to get up and running. Eventually it will run and you can access the Mongo Express server at http://0.0.0.0:8081.
