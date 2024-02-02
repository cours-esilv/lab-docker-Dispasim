FROM nginx:latest
ENV WS_BACK_URL=BACKEND_URL
COPY . /usr/share/ngnix/html
EXPOSE 80
ENTRYPOINT ["nginx", "-g", "daemon off;"]