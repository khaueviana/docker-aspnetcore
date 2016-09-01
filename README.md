# docker-aspnetcore

Installation
------------

Run

```
npm install -g yo
npm install -g bower
npm install -g generator-aspnet
yo aspnet webbasic
cd WebApplicationBasic
docker build -t my-dotnet-app .
docker run -p 80:5000 my-dotnet-app

```

Usage
-----

1. View in http://localhost
