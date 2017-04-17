FROM node:6.9.4-alpine  
MAINTAINER Jhon Edison Castro edisoncastrosanchez@gmail.com  
EXPOSE 8080  
RUN mkdir -p /usr/src/app  
WORKDIR /usr/src/app  
ADD . /usr/src/app  
RUN npm install --production  
CMD ["npm", "start"]  
