# simple docker-compose example

## Install docker-compose

```
curl -L https://github.com/docker/compose/releases/download/1.8.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
```

## Use compose file

```
wget https://raw.githubusercontent.com/paramah/docker-ejabberd/master/examples/docker-compose/docker-compose.yml
```

Edit docker-compose.yml for setup env data (MySQL access, XMPP hostname and admin default username), after edit data run:

```
docker-compose up
```



