FROM quay.io/gascomit/secktor-md
RUN git clone https://github.com/ArctixBots/Ultron /root/ArctixBots
WORKDIR /root/ArctiBots/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
