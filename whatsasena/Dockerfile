FROM fusuf/whatsasena:latest
FROM quay.io/lyfe00011/bot:beta

RUN git clone https://github.com/lyfe00011/whatsapp-bot.git /root/whatsAsena/
RUN git clone https://github.com/Neeraj-x0/Luttappi-WABOT.git /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
