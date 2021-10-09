FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Shadow-Sir-V1/SHADOW-SIR-V2.0 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Chunkindepadayali/media

CMD ["node", "bot.js"]
