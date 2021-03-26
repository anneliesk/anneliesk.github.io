Run CarPal - on my iMac


docker run --name some-mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=Cassidy1$ -d -v hillscarpaldb:/var/lib/mysql mysql:5.7

-d - run the container in detached mode (in the background)
some-mysql - the image to use
-p 3306:3306 - map port 3306 of the host to port 3306 in the container
