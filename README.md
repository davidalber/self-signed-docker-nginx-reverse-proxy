The script in this repository automates the steps in [Self-signed SSL Reverse proxy with Docker](https://medium.com/@oliver.zampieri/self-signed-ssl-reverse-proxy-with-docker-dbfc78c05b41).

```
usage: mkproxy CMD [-p PORT]

Run an NGINX reverse proxy with SSL in front of a specified port.

positional arguments:
 CMD              'up' or 'down'

flag arguments:
 -h, --help       show this help message and exit
 -n, --name NAME  Docker container name (defaults to 'nginx_proxy')
 -p, --port PORT  port to proxy to; required if CMD is 'up'
```