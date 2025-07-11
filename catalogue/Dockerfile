FROM node:18
# we can check node 18 from docker hub in node/tags
EXPOSE 8080
WORKDIR /opt/server
COPY package.json /opt/server/
COPY server.js /opt/server/
RUN npm install
CMD [ "node","server.js" ]