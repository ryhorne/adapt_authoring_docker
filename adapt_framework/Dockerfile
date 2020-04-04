FROM node:lts-stretch-slim
RUN apt-get update && \
    apt-get install -y git
COPY adapt_authoring /adapt_authoring
RUN npm install -g grunt-cli adapt-cli
WORKDIR /adapt_authoring
EXPOSE 5000
CMD node server
