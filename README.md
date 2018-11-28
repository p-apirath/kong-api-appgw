# KONG API GATEWAY
kong-api with force redirect http to https and konga as admin UI for kong   
- http port for direct access app backend pool: `8000`
- http --> https redirect port: `80 --> 443`
- https port: `443`


How to use
- git clone [this repo](/../../)
- docker-compose up -d
- Konga WebUI for Kong: `http://<DNS/Host-IP>:1337`
