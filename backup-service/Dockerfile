# Set up ubuntu image 
FROM ubuntu:18.04

ENV DEBIAN_FRONTEND noninteractive

# install mongodb backup tools 
RUN apt-get update && apt-get install -y mongo-tools

#  install aws cli
RUN apt-get install -y awscli

# copy mongodb backup script to /
#COPY ./test.sh ./

#RUN chmod +x ./test.sh

# Run the command on container startup
CMD ["bash"]
