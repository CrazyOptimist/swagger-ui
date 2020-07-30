# Swagger UI Using Docker Compose

## Description
This is hands-on deployment kit for api documentation according to OpenAPI 3 standards <br />
Authored by [CrazyOptimist](https://www.crazyoptimist.net/about)

## How to use
Put your api doc file 'filename.yaml' into the directory 'swagger' <br />
Create .env file using this command: <br />
```shell
cp .env.example .env
```
Open the .env file and feed this: `FILE_URL=swagger/filename.yaml` <br />
Launch the app 
```shell
docker-compose up -d
```
