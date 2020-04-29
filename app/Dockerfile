FROM node:12

RUN mkdir -p /var/www
ADD ./ /var/www

RUN cd /var/www && npm ci

CMD [ "node", "/var/www/index.js" ]