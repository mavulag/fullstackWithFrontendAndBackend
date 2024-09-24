FROM node

WORKDIR /client

COPY package*.json /client/

RUN npm install

RUN npm install --save-dev @babel/plugin-proposal-private-property-in-object

COPY . /client/

EXPOSE 3000

CMD [ "npm", "start" ]