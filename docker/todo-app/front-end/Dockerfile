FROM node:alpine
WORKDIR /usr/src/app
COPY . .
ADD ./node_modules.tar.gz ./
EXPOSE 3000
ENTRYPOINT ["npm" ,"start"]