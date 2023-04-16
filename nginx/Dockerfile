FROM nginx

# COPY default.conf /etc/nginx/default.conf
COPY default.conf /etc/nginx/conf.d/default.conf

# EXPOSE 4000

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["nginx", "-g", "daemon off;"]