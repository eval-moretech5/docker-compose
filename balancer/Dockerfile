FROM nginx:1.25.2-alpine
ENV PROJECT_DIR=/opt/project
RUN mkdir -p $PROJECT_DIR
WORKDIR $PROJECT_DIR
ADD default.conf /etc/nginx/conf.d/
ADD ssl/ /etc/nginx/ssl/
EXPOSE 80
EXPOSE 443