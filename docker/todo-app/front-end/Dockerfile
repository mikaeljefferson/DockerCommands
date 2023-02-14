FROM node:14-alpine3.12
EXPOSE 3000
ADD node_modules.tar.gz ./
WORKDIR /
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
