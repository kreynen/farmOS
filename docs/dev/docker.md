# Docker

farmOS can be installed locally with [Docker](https://www.docker.com).

Requirements:

* Docker
* Docker Compose

Run the following command from the farmOS repository's root directory:

    sudo docker-compose up

Then go to `http://localhost` in your browser to complete installation.

When prompted for database credentials, use the following:

* Name: `farm`
* User: `farm`
* Password: `farm`
* Hostname (under "Advanced"): `db`

Known issues:

* Email does not work from within the Docker container.

## Drupal Console

To use Drupal Console with the running containers, use the following
command (replace `[command]` with the Drupal Console command you want to
run).

    sudo docker run --rm -v $(pwd)/.data/www:/app --link=farmos_db_1:db --net=farmos_default drupalconsole/console:1.0 --version

Note: this assumes that the repository directory is named `farmOS`.
Docker Compose creates container and network names based on the
directory it is run from, so the `--link` and `--net` flags in the
command might need to be modified based on your setup. You can find the
auto-generated prefix that Docker Compose created by examining your
running containers with `sudo docker ps`.

