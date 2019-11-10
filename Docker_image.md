sudo apt update
sudo apt install nodejs
sudo apt install npm

sudo npm cache clean
sudo npm install n -g

sudo n stable
sudo ln -sf /usr/local/bin/node /usr/bin/node

sudo apt purge -y nodejs npm