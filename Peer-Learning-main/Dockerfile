FROM  node:13-alpine
ENV MONGO_DB_USERNAME = admin \
    MONGO_DB_PWD = peerlearning

RUN mkdir -p /home/app
COPY . /home/app

CMD [ "node", "/home/app/config.js" ]