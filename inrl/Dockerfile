FROM fusuf/whatsasena:latest

RUN git clone https://github.com/fasweeh-fazzz/faz /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/fasweeh-fazzz/media

CMD ["node", "bot.js"]
