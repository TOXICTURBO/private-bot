FROM quay.io/hermit/hermit-ser:latest

RUN git clone https://github.com/TOXICTURBO/private-bot /root/phoenix
WORKDIR /root/phoenix/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
