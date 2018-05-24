FROM node
RUN mkdir -p /src/app
WORKDIR /src/app
COPY package*.json ./
RUN npm install
COPY app.js ./
EXPOSE 3000
CMD [ "node", "/src/app/app.js" ]
