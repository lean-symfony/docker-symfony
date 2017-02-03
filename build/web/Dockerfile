FROM nginx:latest

# Nginx site
RUN rm /etc/nginx/conf.d/default.conf
ADD symfony.conf /etc/nginx/conf.d/

# Timezone
RUN rm /etc/localtime
RUN ln -s /usr/share/zoneinfo/Europe/Berlin /etc/localtime
RUN "date"

