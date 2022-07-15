FROM fusuf/whatsasena:latest

RUN git clone https://github.com/samurai-maker/whatsappub /jsl/Abu
WORKDIR /jsl/Abu
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines

CMD ["node", "index.js"]
