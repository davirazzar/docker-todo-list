FROM node:14-alpine AS todofrontend
WORKDIR /front-end
COPY . .
ADD ./node_modules.tar.gz ./
EXPOSE 3000
CMD ["npm", "start"]
