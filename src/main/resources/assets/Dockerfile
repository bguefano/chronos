FROM nginx:stable-alpine

ENV WEBAPP /usr/share/nginx/html

COPY app $WEBAPP

CMD /bin/sh -c "envsubst < $WEBAPP/scripts/chronos.template > $WEBAPP/scripts/chronos.js && nginx -g 'daemon off;'"
