# zabbix-backup-script
Script for backing up Zabbix configuration and SQL database. Tested on Zabbix version 6.2.6.

## Usage
```
$ chmod +x zabbix-backup-script.sh
$ ./zabbix-backup-script.sh -h
  options:
    -f	backup all zabbix config files in etc, usr, apache-configs  and create a full database dump"
    -s	backup all zabbix config files in etc, usr, apache-configs and create a database dump without the tables 
        history, history_uint, history_text, history_str, history_log, trends, trends_uint and events"
``` 

## Tested Zabbix versions
 - 6.2.6

## Planned / future features
  - Change the script to be more flexible. (PostgreSQL, different configuration paths)

## Contributing
All contributions welcome! If possible you can test the script on different Zabbix versions.

## Warning!
Please check if you use different paths for configuration files. Validate the backup! You are responsible for what you do with this script!
