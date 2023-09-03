FROM nginx

RUN rm /etc/nginx/nginx.conf 

COPY nginx.conf /etc/nginx/nginx.conf

#RUN service nginx restart

ENTRYPOINT [ "nginx" , "-g" , "daemon off;" ]
