FROM linuxserver/code-server:version-v3.11.0

RUN apt-get update
RUN apt-get upgrade -y

RUN apt-get install htop vim tmux -y

RUN curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
RUN sudo apt-get install -y nodejs
