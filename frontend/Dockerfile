FROM ubuntu:16.04

RUN apt-get update

# for react frontend
EXPOSE 4200

# set working directory
ADD . /app
WORKDIR /app

# This is the runtime command for the container
CMD npm start
