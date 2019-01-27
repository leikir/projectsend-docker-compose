# projectsend-docker-compose

### Start the containers for the first time :

`docker-compose up`

`ctrl-c` or `docker-compose down`

Change values in `/config/projectsend/sys.config.php` to match your mysql configuration (see docker-compose.yml).
Be careful hostname must be the name of the service in the docker-compose file (here 'mysql')

Then `docker-compose up`

Visit localhost:8000

Enjoy !
