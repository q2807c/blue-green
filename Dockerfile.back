FROM nginx

COPY etc/nginx/html /etc/nginx/html
RUN chown -R nginx:nginx /etc/nginx

EXPOSE 80 443 8080
STOPSIGNAL SIGTERM
CMD ["nginx", "-g", "daemon off;"]