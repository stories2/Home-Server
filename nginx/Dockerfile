  
FROM nginx:1.20.0

RUN mkdir /usr/share/nginx/well-known

RUN apt update
RUN apt-get install letsencrypt -y
RUN apt-get install vim htop tmux -y
RUN apt-get install cron -y

COPY default.conf /etc/nginx/conf.d/default.conf
#RUN certbot certonly --noninteractive --agree-tos -d kws0.kangnam.ac.kr --register-unsafely-without-email --webroot -w /usr/share/nginx/well-known/

EXPOSE 80
EXPOSE 443
