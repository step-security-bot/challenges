FROM nginx:latest@sha256:593dac25b7733ffb7afe1a72649a43e574778bf025ad60514ef40f6b5d606247
RUN chmod g+rwx /var/cache/nginx/ /var/run /var/log/nginx
COPY ./html /var/www/
COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 8000
