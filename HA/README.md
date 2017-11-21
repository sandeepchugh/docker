#To build and run using HAProxy

docker-compose -f docker-compose-haproxy.yml build
docker-compose -f docker-compose-haproxy.yml up

Launch browser and run http://localhost/api/values

#To build and run using nginx

docker-compose -f docker-compose-nginx.yml build
docker-compose -f docker-compose-nginx.yml up

Launch browser and run http://localhost/api/values


Requires docker for windows - https://download.docker.com/win/stable/Docker%20for%20Windows%20Installer.exe


