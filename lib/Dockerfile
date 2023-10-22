FROM quay.io/hermit/hermit-ser:latest

RUN git clone https://github.com/dzmidhun/aparna-md /root/Aparna
WORKDIR /root/Aparna/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js", "--max_old_space_size=2560"]
