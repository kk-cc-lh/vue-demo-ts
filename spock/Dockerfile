FROM nginx

COPY /spock/nginx.conf /etc/nginx/conf.d/default.conf
COPY /spock/cmd.sh ./
COPY /dist /usr/share/nginx/html/


EXPOSE 80

ENTRYPOINT ["sh", "./cmd.sh"]
