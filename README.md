# CruzHacks 2020 Postgres Test Database
## Dependencies:
 - [Docker Desktop](https://www.docker.com/products/docker-desktop)
### Setup
1. Start the Docker build with `docker-compose -f stack.yml up`. This will also install an Adminer container, which adds a Postgres configuration UI.
2. Share your filesystem with Docker Desktop; you should get a notification after running `docker-compose`. 
2. Determine if the database is up by navigating to Adminer on [http://localhost:8080](http://localhost:8080) 
    - Username: `admin`
    - Password: `test`
#### Tables
 - Hackers
 - Volunteers
 - Mentors
 - Organizers
 - Test 

 
