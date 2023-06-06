# STEP 1 - BACKEND CONFIGURATION
## Installation of Node.js
Update ubuntu
```
sudo apt update
```
Upgrade ubuntu
```
sudo apt upgrade
```
Get location of Node.js software
```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
```
Install Node.js on the server
```
sudo apt-get install -y nodejs
```
Verify the node installation with the command below
```
node -v 
npm -v
```
![Node install validation](./images/nodeJS%20version%20validation.png)

## Creating project directory
Create project directory
```
mkdir Todo
```
![Node install validation](./images/project%20directory.png)

