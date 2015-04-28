#### Very simple first example.

This is a simple example of how to execute a single command within a container. This example echo's "Hello Docker" to stdout. It can be built and run with the following commands:

1. Build your image:
docker build -t nickgs/first-app .

2. Run your container based on your newly built image:
docker run nickgs/first-app

