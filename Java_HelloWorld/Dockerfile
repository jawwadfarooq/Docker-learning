FROM ubuntu:latest 
ADD HelloWorld.class HelloWorld.class
RUN apt-get update \
    && apt-get install -y openjdk-8-jdk 
    
#   && apt-get install -y openjdk-8-jdk \     
#   && rm -rf /var/lib/apt/lists/*

# RUN apk --update add openjdk8-jre 
CMD java HelloWorld
# ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "HelloWorld"]
