FROM java:8
VOLUME /tmp
EXPOSE 9999
ADD /target/draft-gs-template-0.1.0.jar feedback-application.jar
ENTRYPOINT ["java","-jar","feedback-application.jar"]
