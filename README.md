docker-hello-world
==================


Usage
-----

To create the image `billyteves/hello-world`, execute the following command on the docker-hello-world folder:

	docker build -t billyteves/hello-world .

You can now push your new image to the registry:

	sudo docker push billyteves/hello-world


Running your Hello World docker image
-------------------------------------

Start your image:

	sudo docker run -d -p 8080:80 billyteves/hello-world

Hello world!
This source code is copied and modified. 

A big credits to:
**http://www.tutum.co**
