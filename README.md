# Intro

Run gitlab-runner with docker

# Configuration

Create the .env file

```
GITLAB_RUNNER_TOKEN=your-token-here
CI_SERVER_URL=https://gitlab.com/
DOCKER_DEFAULT_IMAGE=docker:20.10.7
```

# Launch gitlab-runner

```
docker-compose run -d
```

## Display logs

```
docker-compose logs -f
```

