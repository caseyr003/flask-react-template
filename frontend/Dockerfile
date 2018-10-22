FROM node:8

RUN apt-get update

# for react frontend
EXPOSE 3000
EXPOSE 5000

# set working directory
ADD . /app
WORKDIR /app

# This is the runtime command for the container
CMD yarn start
