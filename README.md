# KONG API GATEWAY
kong-api with force redirect http to https and konga as admin UI for kong   
- kong port list:
  - port `8080` force redirect to `443`
  - port `8000` direct to backend with http only
  - port `8443` direct to backend with https only
- this `docker-compose.yml` are mapping kong port to:
  - "8000:8000/tcp"
  - "8001:8001/tcp"
  - "443:8443/tcp"
  - "8444:8444/tcp"
  - "80:8080/tcp"
- konga is kong WebUI for admin management

How to use
- git clone [this repo](./)
- docker-compose up -d
- Konga WebUI: http://<DNS/Host/IP>:1337
