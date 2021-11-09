FROM node:alpine
WORKDIR /usr/src/app
COPY . .
ADD ./node_modules.tar.gz ./
EXPOSE 3001
ENTRYPOINT ["npm" ,"start"]