# cloud-computing-project
#Solution installation guide

##Install Git
1. sudo apt install git
2. git clone URL
3. type in username and password which is token generated on github website in settings

## Install Docker
1. sudo apt install apt-transport-https ca-certificates curl software-properties-common
2. curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - 
3. eb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
4. sudo apt update
5. sudo apt install docker-ce

To check the status of the docker use this command:
sudo docker info

6.sudo apt install docker-compose
