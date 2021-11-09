FROM mjgargani/puppeteer:trybe1.0
WORKDIR /usr/src/app
COPY . .
ADD ./node_modules.tar.gz ./
ENTRYPOINT ["npm" ,"test"]