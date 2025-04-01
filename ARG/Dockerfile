FROM almalinux:9
ENV course="Devops with AWS" \
    trainer="Anil" \
    Duration="120HRS"
#username is KEY and some_user is default value  
ARG ${username:-some_user}
RUN echo "Hello user: $(username)"
CMD [ "sleep" ,"100" ]