apache server running commands
docker build -t apache_image:1.0 .
docker run --name myapache -d -p 80:80 apache_image:1.0
