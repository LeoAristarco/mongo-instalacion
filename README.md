# mongo-instalacion (2.4.14)


llave pública GPG y crear el archivo de fuentes:

$ sudo apt-key adv --keyserver keyserver.ubuntu.com --recv 7F0CEB10
...
$ echo 'deb http://downloads-distro.mongodb.org/repo/debian-sysvinit dist 10gen' | sudo tee /etc/apt/sources.list.d/mongodb.list
...


$ sudo apt-get update
...
$ sudo apt-get install mongodb-10gen
...


$ sudo apt-get install -o apt::architecture=amd64 mongodb-10gen
