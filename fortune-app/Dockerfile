#the base image that we will be building off of.
FROM ubuntu

#Move files from our host machine into this image.
ADD start.sh /start.sh

#Run some commands to build our image how we want it.
RUN apt-get update -y && \
    apt-get install fortune cowsay -y && \
    chmod a+x /start.sh

#The default initial program to call when running the container.
CMD ["/start.sh"]
