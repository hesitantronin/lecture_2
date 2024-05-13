FROM nginx:latest
LABEL maintainer="Ronin van Egdom studNr.(1053927)"
LABEL description="This image contains the frontend of the cddb Album application"
LABEL version="version1.0"

EXPOSE 80

COPY src /usr/share/nginx/html
COPY resources/nginx.conf /etc/nginx/nginx.conf
