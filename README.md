# api
API for app

[![gitter](https://badges.gitter.im/Join%20Chat.svg)][gitter]
[![License Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=true)](http://www.apache.org/licenses/LICENSE-2.0)

# www
Website

https://github.com/faas-ovh/app.git

https://github.com/paas-info/www


TODO:

buttons
https://getbootstrap.com/docs/4.0/components/buttons/


## Run Service on linux

Note if you're new to Unix: 
/var/www/myapp/app.js should have 
#!/usr/bin/env node
 
on the very first line.

Copy your service file into the /etc/systemd/system.

Start it with systemctl start myapp.

Enable it to run on boot with systemctl enable myapp.

See logs with journalctl -u myapp

## screen
The screen will detach and survive you logging off. Then you can get it back back doing screen -r. Hit up the screen manual for more details. You can name the screens and whatnot if you like

    screen
    node myserver.js
    
>>CTRL-A then hit D
