FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#THIS EXECUTES IF ANY USER USES THIS IMAGE AS THEIR BASE OS
ONBUILD  COPY index.html  /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]