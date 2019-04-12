# nginx-example

This is simple proxy example to mitigate same origin.

Run:

`docker-compose up --build`

then go to:

http://localhost:8080/app


The `/app` is where the dotnet host app is located.  The remote website (random nodejs pull from docker hub) is set to the default site to avoid path issues with the legacy site.

The iframe in the middle of the page with the Nicholas Cage image is from another origin.