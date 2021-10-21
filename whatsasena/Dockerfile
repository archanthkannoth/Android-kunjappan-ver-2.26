FROM fusuf/whatsasena:latest

RUN git clonehttps://github.com/archanthkannoth/Android-kunjappan-ver-2.26 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
