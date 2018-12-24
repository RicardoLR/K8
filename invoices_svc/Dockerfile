FROM node:carbon
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "npm", "start" ]


# docker build -t dockerthrafik/invoices_svc:v1 .
# docker push dockerthrafik/invoices_svc:v1
