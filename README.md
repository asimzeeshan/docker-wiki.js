# docker-wiki.js

This repo has a docker-compose to run [wiki.js](https://js.wiki/) &amp; MariaDB since the [official documentation](https://docs.requarks.io/install/docker) lists it with PostgreSQL

### Install

clone this repo in say `/home/wiki.js`, run
```sh
docker-compose up --build -d
```

Wiki.js is running at http://ip or http://fqdn (e.g. wiki.imda.one)
