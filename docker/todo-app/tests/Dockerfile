FROM mjgargani/puppeteer:trybe1.0
ADD node_modules.tar.gz ./
WORKDIR /
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "test" ]
