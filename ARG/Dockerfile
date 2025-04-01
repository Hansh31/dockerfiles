FROM almalinux:9
ENV course="Devops with AWS" \
    trainer="Anil" \
    Duration="120HRS"
#username is KEY and some_user is default value  
ARG USERNAME=Anil
ENV USERNAME=${USERNAME}
RUN echo "Hello user: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep" ,"100"]