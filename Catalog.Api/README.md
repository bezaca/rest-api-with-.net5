# Rest Api with .Net5

This project is a rest-api code in .Net5 with Mongo as a database, that implements asynchronous tasks, healthcare checks, and a few more things.

## Mongo container configuration
This API works with a Mongo Database, to keep things simple you can use Docker to create a container with mongo.   Running this command : 
```bash
docker run -d --rm --name mongo -p 27017:27017 -v mongodbdata:/data/db -e MONGO_INITDB_ROOT_USERNAME=mongoadmin -e  MONGO_INITDB_ROOT_PASSWORD=Pass#word1 mongo
```
This command include the environment variables for an authenticate user.
