# specify base image
from node:alpine

# working directory declaration
workdir /usr/app

# install some dependencies
copy ./package.json ./
run npm install

# copy working directory
copy ./ ./

# default cmd
cmd ["npm", "start"]

# 192.168.99.100:8080