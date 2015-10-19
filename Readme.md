# Summary

A simple python script which is able to produce a digest mail on the most recent activities of an oxwall community software (see http://www.oxwall.org/).

# Installation

Install the following dependencies:
```bash
sudo apt-get install python-mysqldb
sudo apt-get install python-sqlalchemy
sudo apt-get install python-jinja2
```

Adapt the configuration.py to fit your system settings.

Add the script to the cron:
```bash
crontab -e
```
