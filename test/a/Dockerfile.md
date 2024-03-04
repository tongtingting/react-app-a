FROM node

COPY . .

RUN npm install -g http-server --verbose

CMD ["http-server ."]


asasdasdasd
