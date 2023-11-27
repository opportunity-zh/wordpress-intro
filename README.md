# WordPress
WordPress is the most used CMS on the internet. But this does not mean it's the best. Maybe it's just the easiest to use. In this lesson you create your first WordPress Project, you learn how WordPress is structured and how to install and use plugins.


## Inhalt
1. [Use with Docker](#use-with-docker)  
2. [Settings](#settings)  
    2.1 [Allgemein](#allgemein)  
    2.2 [Permalinks](#permalinks)  
3. [Install your first Plugin](#install-your-first-plugin)
4. [Install your first Theme](#install-your-first-theme)



## Use with Docker
To use WordPress with Docker, you need to have **Docker** and **Compose** installed.

1. Check if **docker compose** is installed. Copy this in your terminal.
```bash
docker compose version
```
2. Create a directory (with your terminal) called **wordpress** and navigate into it
```bash
mkdir wordpress
cd wordpress
```
3. Download docker-compose.yml from this repository and move it in your new created **wordpress Folder**
4. Start up the Docker Container
```bash
docker compose up -d
```
5. Check if docker processes are running, type the following in your terminal
```bash
docker ps
```
6. If you see processes you can move on
7. Open Browser and type the following in the url bar
```bash
localhost:8080
```
8. Go through the WordPress Installation Process (Remember your Password)
9. Work on your project
10. If the day is over - shutdown the docker container
```bash
docker compose down
```





