FROM ubuntu:22.04
RUN apt update && apt install -y curl
RUN bash -c "$(curl -L https://raw.githubusercontent.com/wulabing/V2Ray_ws-tls_bash_onekey/master/install.sh)"
CMD ["v2ray", "-config", "/etc/v2ray/config.json"]
