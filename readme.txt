from : https://medium.com/dev-tricks/apache-and-php-on-docker-44faef716150

1. Clone this repo
2. cd into it
3. build docker image: (may need sudo)

	$ docker build -t myuser/mysite .

4. list docker images:
	$ docker images

5. run/start docker image:
	$ docker run -p 8080:80 -d myuser/mysite /usr/sbin/apache2ctl -D FOREGROUND

6. list running docker containers:
	$ docker ps

7. see running app at http://localhost:8080



