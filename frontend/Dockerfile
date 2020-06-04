FROM nginx:stable-alpine as production-stage
WORKDIR /usr/share/nginx/html
COPY img/ ./img
COPY css/ ./css
COPY html/index.html .

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]