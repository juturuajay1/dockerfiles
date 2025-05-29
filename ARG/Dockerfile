FROM almalinux:9
ENV course="Devops with AWS" \
    trainer="Ajay" 
#here user1 is key, someuser is default value
ARG ${username:-some_user}
RUN echo "Hello user ${username}" 
RUN echo "Hello ${trainer}" > /tmp/devops.txt
CMD ["sleep","100"]