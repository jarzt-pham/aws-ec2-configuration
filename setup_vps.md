## EC2
Connect
> ssh -i ./<key>.pem <username>@<host> 

## Install Node Js
Install package through curl cli
> curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
Install to ubuntu
> sudo apt-get install -y nodejs
Check version
> node -v

## Install nginx
Install package through ubuntu
> sudo apt install nginx
Check version
> nginx -v
Allow firewall
> sudo ufw allow 'Nginx HTTP'

## Check status of service in VPS (ubuntu)
>systemctl status <service_name>

## Install pm2
Install cli
> sudo npm install pm2@latest -g

Read PM2 at https://pm2.keymetrics.io/
> pm2 start server.js --name "hello-world" --watch

