# Docker Compose Context ECS
An example of how to quickly deploy docker containers to ECS

## Configuration Credentials for AWS CLI

To set env vars for the current active workspace
```
export AWS_ACCESS_KEY_ID=
export AWS_SECRET_ACCESS_KEY=
export AWS_DEFAULT_REGION=us-east-1
```

To persist after each gitpod workspace
```
gp env AWS_ACCESS_KEY_ID=
gp env AWS_SECRET_ACCESS_KEY=
gp env AWS_DEFAULT_REGION=us-east-1
```

## How to deploy docker compose with ECS

```
docker context create ecs myecscontext
```

```
docker-compose up
```

## References

https://docs.docker.com/cloud/ecs-integration/