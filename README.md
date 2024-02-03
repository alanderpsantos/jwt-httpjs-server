# JWT HTTP(JS) Server
A NodeJS HTTPS server with Auth by JWT


### Create a self signed certificate

```bash
$ openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /path/to/your/jwt-httpjs-selfsigned.key -out /path/to/your/jwt-httpjs-selfsigned.crt
```

### Enviroment Variables

```bash
$ export SELF_SIGNED_KEY=/path/to/your/jwt-httpjs-selfsigned.key
$ export SELF_SIGNED_CERT=/path/to/your/jwt-httpjs-selfsigned.cert
```


### Installing Dependencies

```bash
$ npm install
```

### Run

```bash
$ DEBUG=test:* npm start
```
