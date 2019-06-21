# manga-py-docker

### Docker

1. Install docker
  - Summary https://docs.docker.com/install/
  - Mac https://docs.docker.com/docker-for-mac/install/
  - Windows https://docs.docker.com/docker-for-windows/install/

2. Install manga-py 
```bash 
docker pull mangadl/manga-py
```

3. Run it
```bash
docker run -it mangadl/manga-py
```

###### or

### Docker-compose:

1. Install docker compose https://docs.docker.com/compose/install/

2. Download manga-py-docker https://github.com/yuru-yuri/manga-py-docker/archive/master.zip

3. Unzip it

4. Run compose
```bash
# build docker
docker-compose build
# run it
docker-compose run manga_py
```
