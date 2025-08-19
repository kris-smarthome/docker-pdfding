# docker-pdfding
Docker compose files, local pdfding install 

Services:

- pdfding: PDF document management

## usage
Clone this repository to your local machine, edit the config file to match your environment, and run docker compose.

```bash
git clone https://github.com/kris-smarthome/docker-pdfding.git pdfding/
cd pdfding
nano .env
docker compose up -d
```

> [!NOTE]
> This stack assumes the use of Traefik, remove labels and networks if Traefik is not used. 