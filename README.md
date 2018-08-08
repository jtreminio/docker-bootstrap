# Docker Bootstrap

### Installs

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)
* [Traefik Proxy](https://traefik.io/)
* [Watchtower](https://github.com/v2tec/watchtower)

### Instructions

* Copy `.env.dist` to `.env`
* Set all values
* Run `./init`

### Config values

* `SERVER_IP` IP of server
* `SSH_USER` SSH username
* `SSH_PRIVATE_KEY` Location of SSH private key on your local machine
* `LE_EMAIL` Email addressed used for Let's Encrypt certificates generated
    via Traefik

Full blog post on usage
[can be found here](https://jtreminio.com/blog/setting-up-a-static-site-with-hugo-and-push-to-deploy).
