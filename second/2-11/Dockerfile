FROM ubuntu:20.04

RUN apt update && apt install -y vim
# apt update
# apt install -y vim
# &&でつなげると、前のコマンドが成功した場合にのみ次のコマンドを実行する
# -yは、apt installのときに、yes/noを聞かれたときに、yesを自動で選択するオプション

COPY ./.vimrc /root/.vimrc

CMD date +"%Y/%m/%d %H:%M:%S ( UTC )"