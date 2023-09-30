FROM ubuntu:20.04

RUN apt update && apt install -y vim

COPY ./.vimrc /root/.vimrc

CMD date +"%Y/%m/%d %H:%M:%S ( UTC )"