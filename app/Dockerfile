FROM node:8

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm ci --only=production
RUN ls -al
COPY . .
RUN ls -al

#EXPOSE 8080
#CMD [ "npm", "start" ]
