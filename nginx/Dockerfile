# Production environment

# nginx is web server we use as a Proxy to route requests to our React app and our API
FROM nginx

COPY default.conf /etc/nginx/conf.d/default.conf

# only when deploying to Heroku!
# CMD /bin/bash -c "envsubst '\$PORT' < /etc/nginx/conf.d/default.conf > /etc/nginx/conf.d/default.conf" && nginx -g 'daemon off;'

