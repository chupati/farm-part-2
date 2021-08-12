# farm-part-2
FARM Stack with Docker Compose - Part 2

Once you copy the repo you can type the following command assuming you have Docker Compose installed on your machine.

docker-compose up

You can access the article write up that explains the code and configuration by visiting:
https://medium.com/codex/creating-a-farm-stack-dev-environment-with-docker-compose-part-2-of-3-fastapi-9ee7ab644809

You may notice that the mongo-express service may fail a few times. The service is waiting for the MongoDB service to get up and running. Eventually it will run and you can access the Mongo Express server at http://0.0.0.0:8081.

If you are running this project on your Mac and happen to be running it in your "Documents" folder, you may encounter permission issues. Please add the "documents" folder or your project folder to the "File Sharing" section in the "Docker Desktop" preferences.

For more information go to https://docs.docker.com/docker-for-mac/#file-sharing.
