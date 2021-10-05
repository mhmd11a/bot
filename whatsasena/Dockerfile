FROM fusuf/whatsasena:latest

RUN git clone https://github.com/mhmd11a/bot /root/bot
WORKDIR /root/bot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
