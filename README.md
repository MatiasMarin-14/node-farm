# node-farm

A simple node website with 5 items for shopping and their descriptions.

-----

It is in a docker container.
All dependencies are in the container.

----
RUNNING THE CONTAINER
----
The container can be built by going to 
`$cd path/to/repo/stater`
The folder should contain a Dockerfile

Running the command
`docker build -t node-farm .`
will build the container

Once the container is built, it can be ran with the command:
`docker run -p 127.0.0.1:8000:8000 node-farm`

You should now be able to see the website on 
`127.0.0.1:8000`
on your favourite browser
