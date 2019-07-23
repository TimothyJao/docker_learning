FROM node:10.13.0-alpine
WORKDIR /my_app/

COPY package.json /my_app/

RUN npm install

COPY . /my_app/

CMD ["node", "petFacts.js"]






