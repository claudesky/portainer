# Portainer in docker-compose

Easily launch portainer with docker-compose.

Meant to be used with [claudesky/local-webserver](https://github.com/claudesky/local-webserver)

## Usage

### (optional) Create a docker-compose.override.yml

```
vim ./docker-compose.override.yml
```

Make any changes you want to override the base docker-compose file.

### Spin up the service

```
sudo docker-compose up -d
```


### Note:

By default, the service does not publish any ports.

You can use the add-site script if you are using [claudesky/local-webserver](https://github.com/claudesky/local-webserver) to give the new container a subdomain on your localhost.
