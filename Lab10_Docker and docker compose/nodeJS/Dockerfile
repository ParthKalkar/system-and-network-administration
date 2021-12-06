FROM node:8 
 
RUN apt-get update && apt-get install -y nodejs && apt-get install -y build-essential
COPY ./easy-node-authentication /app
WORKDIR /app
RUN npm install
#COPY hello.py .
#CMD ["/usr/bin/node", "server.js"]
CMD ["node", "server.js"]
