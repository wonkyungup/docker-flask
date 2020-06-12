FROM netsarang/centos-8

WORKDIR /root
RUN mkdir -p /root/source

RUN dnf update -y

##python
RUN dnf install python3 -y
RUN dnf install python3-pip -y

##sqlite3
RUN dnf install sqlite -y

##pip
RUN pip3 install Flask --upgrade pip
RUN pip3 install matplotlib --upgrade pip 
#RUN pip3 install PyGObject --upgrade pip

EXPOSE 5000
