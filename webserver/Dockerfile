FROM nginx
RUN apt-get update
RUN apt-get install -y curl
COPY nginx.conf /etc/nginx/nginx.conf
COPY default.conf /etc/nginx/conf.d/default.conf
RUN mkdir -p /src/webserver
WORKDIR /src/webserver
COPY start.sh ./
EXPOSE 8080
CMD [ "/src/webserver/start.sh" ]
