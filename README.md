# Veranstaltungsdatenbank

## Deployment mit Docker

    docker build https://github.com/wichmann/veranstaltungsdatenbank.git -t verandb
    docker run -p 5000:5000 -d verandb

## Deployment mit Docker Compose

    git clone https://github.com/wichmann/veranstaltungsdatenbank.git
    docker compose up -d
