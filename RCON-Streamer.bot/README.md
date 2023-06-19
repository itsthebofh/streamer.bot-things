The webrcon server I use here is the one created by forewing https://github.com/forwing/webrcon-server they did all the work on that I just setup the Streamer.Bot side of things. 

In the file docker-compose.yml you will find my docker compose file, based on forewing's example file. 

If you are running a docker swarm cluster I have also included my swarm file, which was branched from forewing's example, with traefik setup as the front end proxy and cloudflare as the SSL Cert provider. 

I have also included my config.json which was taken from the example file on forewing's repo. 

Included is what I use in streamer.bot to connect to the webrcon api endpoint and send the command across.  

A couple things to caution you on with this RCON server setup. 

**There is not authentication method implemented in my setup.** 

**Make sure to secure this setup if you expose it to internet traffic as this could cause your game server to be hacked.** 

If you have any issues please let me know and I will see what I can do to help you out. 

