# eveebaby
Etherminer monitor watchdog

## Setting
```
git clone https://github.com/v2tmobile/eveebaby.git
cd eveebaby
chmod gpu-stats.sh
chmod u+x letgo.sh
chmod u+x evee
# crontab setting
* * * * * /bin/bash -c "~/.bashrc; /home/evee/eveebaby/evee >> /home/evee/eveebaby/watchdog.log"
```
