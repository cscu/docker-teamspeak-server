# docker-teamspeak

An easy way to spin up a teamspeak server.

## Building docker-teamspeak

To build the docker image:

	$ git clone https://github.com/cscu/docker-teamspeak.git
	$ docker-compose build


## Running docker-teamspeak

With docker-compose, (building and) running a teamspeak server is trivial, just execute the line below in your cloned repository, which will build and run the server as a daemon.

	$ docker-compose up -d 

## Server Admin Token

When first running the server, you will need to access the server admin token. After running the server, run `$ docker logs teamspeak_server_1` to view the recent output from the server. Your admin token will be in the output.

# Attribution

This repository is based off of [overshard/docker-teamspeak](https://github.com/overshard/docker-teamspeak). 