FROM nginx

# Remove the default config
RUN rm /etc/nginx/conf.d/default.conf

# Replace with custom config
COPY nginx.conf /etc/nginx/conf.d/