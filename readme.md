# Docker container for linux vrising server 

using Wine in an ubuntu container

This isn't really meant to be a guide, just publishing because at the moment not much info on setting this up out there. I'm no docker expert so there's probably a better way to go about this. Sorry if these steps aren't 100% accurate: 

1. Clone the repo
git clone https://github.com/Googlrr/V-Rising-Docker-Linux

2. CD to the directory
cd V-Rising-Docker-Linux

3. Modify the ServerGameSettings.json and ServerHostSettings.json for whatever you want. 

4. Build the image
sudo docker-compose build 

5. Modify docker compose, set a path for where you want your saves. Set the save and settings directories

6. compose
sudo docker-compose up -d 

Really messy setup but this was the only way I could figure out how to work it lol. Never used Wine before. Hope for a native linux server soon! 

