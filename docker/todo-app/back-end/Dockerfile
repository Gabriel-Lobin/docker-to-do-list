FROM node:alpine
WORKDIR /usr/src/app
EXPOSE 3001
COPY . .
ADD ./node_modules.tar.gz ./
ENTRYPOINT ["npm" ,"start"]