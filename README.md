# WordPress
WordPress is the most used CMS on the internet. But this does not mean it's the best. Maybe it's just the easiest to use. In this lesson you create your first WordPress Project, you learn how WordPress is structured and how to install and use plugins.


## Inhalt
[Use with Docker](#use-with-docker)  
[Settings](#settings)  
[Install your first Plugin](#install-your-first-plugin)  




## Use with Docker
To use WordPress with Docker, you need to have **Docker** and **Compose** installed.

1. Check if **docker compose** is installed. Copy this in your terminal.
```bash
docker compose version
```
2. Create a directory called wordpress and navigate into it
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

## Basic Settings





## Install your first Plugin
WordPress offers a simple way to extend its functionality. It allows you to install plugins.

1. Type the following in your URL Bar
```bash
localhost:8080/wp-admin
```
2. Log in if you're not already did
3. Open the **Plugins** Tab
4. On the upper left click on **"Installieren"**
5. Type in the Searchbar on the right side
```bash
BetterDocs
```
6. Click on **"Jetzt installieren"**
7. If it finished the installation, click on **"Aktivieren"**




