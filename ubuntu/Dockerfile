FROM ubuntu:22.04
RUN apt update && apt install wget build-essential libncursesw5-dev -y
RUN apt install libssl-dev -y
RUN apt install libsqlite3-dev -y
#RUN apt install tk-dev  
RUN apt install libgdbm-dev -y
RUN apt install libc6-dev -y 
RUN apt install libbz2-dev -y
RUN apt install libffi-dev zlib1g-dev -y
RUN apt install software-properties-common -y
RUN add-apt-repository ppa:deadsnakes/ppa && apt update 
#RUN apt install python3.11 -y
#RUN apt install python3-pip -y
#RUN pip install -U cqlsh

ENTRYPOINT ["/bin/bash"]
