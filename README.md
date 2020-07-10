# Status-updater-script
Status script used for Nahoko server bot to refresh status every 3 minutes (it's made for learning purposes, it's not recommended to use it on own hand)

How to install? It's simple

To clone files do:
`git clone https://github.com/lenforiee/status-updater.git`

Now setup config and delete `.example` from name

Next do `npm install` to install all needed modules to run a script

You might have to install also pm2 as cron is based on this module, to install it just type:
`npm install pm2 -g`

Now just run both JavaScript files using:

`pm2 start status.js` and `pm2 start cron.js`