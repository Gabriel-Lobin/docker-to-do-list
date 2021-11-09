FROM node:14-alpine
WORKDIR /usr/src/app
EXPOSE 3000
COPY ./ ./
ADD ./node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]