check_couchdb
=============

NodeJS Version of check_couchdb by FreshX

Install
-------

`npm -g i check_couchdb`

This will place a global bin in your path for `check_couchdb`. Now you can use it in Nagios as a command.

Usage : --version        show program's version number and exit
        -h, --help       show this help message and exit
        --server=SERVER  Servername to connect to
        -H SERVER        Alias for --server
        --ssl            Enable SSL
        --user=USER      Authenticate as user
        --pass=PWD       Authenticate with pass
        --port=PORT      Connect to non default port (5984 or 6984
        --less           Dump less performance values
        --debug          Dump debug info's while running
