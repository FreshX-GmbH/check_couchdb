check_couchdb
=============

NodeJS Version of check_couchdb by FreshX

Install
-------

```
$ npm -g install FreshXOpenSource/check_couchdb
.... npm output ...
check_couchdb@0.3.0 /usr/lib/node_modules/check_couchdb```

Now link the check_couchdb binary into your nagios/centreon installation :

`ln -s <path from your npm installation above>/bin/check_couchdb <path to your nagios plugins> `

i.e. on RedHat Systems this would look like :

`ln -s /usr/lib/node_modules/check_couchdb/bin/check_couchdb /usr/lib64/nagios/plugins/check_couchdb``

Usage
-----
This will place a global bin in your path for `check_couchdb`. Now you can use it in Nagios as a command.
```
Usage: check_couchdb   < -H HOSTNAME | --host >  host to connect to
                       [ -h | --help ]           show help ]
                       [ -s | --ssl  ]           enable SSL, default NO ]
                       [ -u | --user USERNAME ]  username to connect with ]
                       [ -p | --pass PASSWORD ]  password to connect with ]
                       [ -P | --port PORT ]      port to connect to, default 5984 (nonssl), 6984 (ssl) ]
                       [ -d | --debug ]          enable debug mode ]
                       [ -l | --less ]           dump less permformance data ]```
