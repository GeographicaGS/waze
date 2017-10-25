# WAZE

SALES management solution based in CARTO.

## How to mount WAZE in your local environment

Run these clones inside this repo directory:
- `git clone git@github.com:GeographicaGS/waze-api.git api`
- `git clone git@github.com:GeographicaGS/waze-www.git www`

### API

- Run `docker-compose -f docker-compose.dev.yml run api npm install`.
- Run `docker-compose -f docker-compose.dev.yml up api`.
