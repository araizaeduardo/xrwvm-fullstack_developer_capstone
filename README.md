# coding-project-template

### Because IBM Code Engine fails so many times, I installed locally docker, python3, pip and nodejs

This is done under Linux mint 21.1 Cinnamon, Kernel 5.15.0-91-generic, based on Ubuntu 22.04

# Installing Docker
sudo apt update
sudo apt install apt-transport-https ca-certificates curl gnupg

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker.gpg

echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu jammy stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null


sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

# Installing Python 3.10 and pip

```
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update 
sudo apt install python3.10
sudo apt install python3-pip
```

# Installing NodeJs

```
sudo apt-get install curl python-software-properties software-properties-common 
curl -sL https://deb.nodesource.com/setup_21.x | sudo bash - 
```

