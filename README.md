KHCouchdb_uuids_dos
===================

DoS attack on an Apache CouchDB &lt;= 1.5.0

INSTALL
------

Install ruby dependencies:

* net/http
* net/ping
* json

HOW TO
------

    * ruby exploit.rb http://host
    * ruby exploit.rb http://host COUNTS

EXAMPLE
-------

    ruby exploit.rb http://localhost:5984 99999999