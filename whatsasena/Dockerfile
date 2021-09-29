FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Aqua-Snake/Cbot /root/Cbot
WORKDIR /root/Cbot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
