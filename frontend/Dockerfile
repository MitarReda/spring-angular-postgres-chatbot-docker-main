FROM  nginx:alpine
COPY ./nginx.conf /etc/nginx/conf.d/default.conf
COPY dist/frontend/browser /user/share/nginx/html
EXPOSE 80
