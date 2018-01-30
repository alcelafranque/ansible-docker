FROM debian:stretch
MAINTAINER alce-lafranque

#Installation des paquets 
RUN apt-get -q -y update \
    && DEBIAN_FRONTEND=noninteractive apt-get -q -y upgrade \
    && apt-get -q -y install \
        python-dev \
        python \
        python-pip \
        python-virtualenv \
        git-core \
        vim \
        python-dev \
        python-wheel \
        curl \        
        python3 \        
        rsync \        
        libxslt1-dev \
        libgeos-c1v5 \
        libgeos-dev \ 
        wget 



RUN  echo "deb http://ppa.launchpad.net/ansible/ansible/ubuntu trusty main" >> /etc/apt/source.list && apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367 && apt-get -q -y update && apt-get -q -y install ansible
