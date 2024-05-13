FROM mcr.microsoft.com/dotnet/aspnet:8.0
LABEL author="Ronin van Egdom studNr.(1053927)"
LABEL description="This image contains the backend/API of the cddb Album application"
LABEL version="version1.0"

WORKDIR /app

COPY . .

EXPOSE 8080

ENTRYPOINT [ "dotnet", "Album.Api.dll" ]