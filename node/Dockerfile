FROM node:20-slim

WORKDIR /usr/src/app

RUN apt update && \
    apt install -y wget netcat && \
    wget -q -O /usr/bin/wait-for https://raw.githubusercontent.com/eficode/wait-for/v2.2.4/wait-for && \
    chmod +x /usr/bin/wait-for

EXPOSE 3000

#CMD ["node", "index.js"]