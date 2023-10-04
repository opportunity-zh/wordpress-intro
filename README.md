# WordPress
WordPress is the most used CMS on the internet. But this does not mean it's the best. Maybe it's just the easiest to use.


## Inhalt
[Use with Docker](#use-with-docker)




## Use with Docker
To use WordPress with Docker. You need to have installed **Docker** and **Compose**

1. Check if **docker compose** is installed. Copy this in your terminal.
```bash
docker compose version
```
2. Create Directory called wordpress and navigate into it
```bash
mkdir wordpress
cd wordpress
```
3. Download docker-compose.yml File and move it in your new created **wordpress Folder**
4. Run Docker Container
```bash
docker compose up -d
```
5. Check if docker processes are running
```bash
docker ps
```
6. Open Browser and type the following in the url bar
```bash
localhost:8080
```
7. Go through the WordPress Installation Process (Remember your Password)
8. Work on your project
9. Shutdown docker Containers
```bash
docker compose down
```
