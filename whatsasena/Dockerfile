FROM fusuf/whatsasena:latest

RUN git clone https://github.com/dumiyh678/QUEEN-TIKIRI-BY-DUMINDU /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
