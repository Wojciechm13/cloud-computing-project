# cloud-computing-project
Wojciech Mielczarek
# Solution installation guide

## Install Git
```bash
1. sudo apt install git
2. git clone URL
 ```
 type in username and password which is token generated on github website in settings

## Install Docker
Install the prerequisite packages
```bash
sudo apt install apt-transport-https ca-certificates curl software-properties-common
```
Download the docker repo key
```bash
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
Add the docker repo
```bash
sudo add-apt-repository "deb [arch=amd64]  
https://download.docker.com/linux/ubuntu bionic stable
```
Update the packages available on the repository
```bash
sudo apt update
```
Install the docker
```bash
sudo apt install docker-ce
```
Test if the installation was successfull 
```bash
sudo docker run hello-world
```
Install docker compose tools
```bash
sudo apt install docker-compose
```
Build and load the composition
```bash
sudo docker-compose up
```
