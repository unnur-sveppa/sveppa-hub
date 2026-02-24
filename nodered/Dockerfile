# Use the official Node-RED image as the base
FROM nodered/node-red:latest

# This ensures the container stays in the right timezone
USER root
RUN ln -snf /usr/share/zoneinfo/UTC /etc/localtime && echo UTC > /etc/timezone
USER node-red