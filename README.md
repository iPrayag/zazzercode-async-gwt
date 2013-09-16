
Compile
=======

`$ mvn clean compile`
`$ mvn gwt:compile`

eclipsify 
=========

`$ mvn eclipse:eclipse`


[Run in dev mode](http://stackoverflow.com/a/3599131/432903)
===============

`$ mvn compile gwt:run`

Run using jetty
===============
`$ mvn jetty:run`

war
===
`$ mvn package`
`$ sudo cp target/gwt20-managed-rpc.war /usr/local/AT_7028/webapps/`
`$ /usr/local/AT_7028/bin/startup.sh`

browse
======

`http://localhost:8080/gwt20-managed-rpc/`
