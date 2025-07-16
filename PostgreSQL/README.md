Using the `-p` flag on the command line:

```sh
docker compose -p myproject up
```

Using the `COMPOSE_PROJECT_NAME` environment variable:
Set this variable in your shell or environment to define the project name for all Compose commands in that session.

```sh
export COMPOSE_PROJECT_NAME=myproject
docker compose up
```

Using the directory name (default behavior):
If neither the `-p` flag nor the environment variable is set, Docker Compose uses the name of the directory containing your `docker-compose.yml` file as the project name.