<!-- @format -->

## Build Image

docker build -t weather-api .

## Run

docker run --env-file .env weather-api
