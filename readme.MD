# WordPress with Traefik `docker-compose`

Pretty straightforward setup for `docker-compose`. 

## Usage

Clone or download the repository. Update necessary settings in `docker-compose.yml`. Make sure to point the "domain" added in `traefik.frontend.rule` is pointing to your docker IP - most cases `localhost`.

Run `docker-compose up -d`.