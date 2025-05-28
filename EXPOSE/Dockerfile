FROM almalinux:9
RUN dnf install nginx -y
#expose will give just information, not changing any functionality
EXPOSE 80 
CMD ["nginx", "-g", "daemon off;"]