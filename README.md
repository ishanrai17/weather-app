# Weather App

A dashboard to track realtime weather

Docker Commands
docker build -t weather-app .
docker run -it --volume "$(pwd)":/usr/src/weather-app weather-app

# Run server
docker run -p 3000:3000 --volume "$(pwd)":/usr/src/weather-app weather-app