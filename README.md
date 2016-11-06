zabbix-dynamic-pdf-report
=========================

This originates from https://github.com/spy86/Zabbix_/zabbix-dynamic-pdf-report
and the goal of this fork is to create a standalone git repository
together with some installation instructions.

Also to make sure it works 100% with Zabbix 3.0 (LTS)


Installation
------------
```
#copy sample to real config
cp config.inc.sample.php config.inc.php

#edit to match your environment
nano config.inc.php

```


develop
-------

* clone `https://github.com/kmpm/zabbix-dynamic-pdf-report`
* Install PHP `sudo apt-get install php7.0 php7.0-cli`