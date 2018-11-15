# KONG API GATEWAY
**With force redirect http to https**
- http port for direct access app backend pool: `8000`
- http --> https redirect port: `80 --> 443`
- https port: `443`

How to use
- git clone https://vca.ais.co.th/ecomos/containers/kong-api-appgw.git
- docker-compose up -d
- Konga WebUI for Kong: `http://<DNS/Host-IP>:1337`