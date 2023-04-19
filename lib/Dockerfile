FROM fusuf/whatsasena:latest

RUN git clone https://github.com/HBMods-OFC/HBWABot-v2 /HBMods-OFC/HBWABot-v2

WORKDIR /HBMods-OFC/HBWABot-v2

ENV TZ=Africa/Harare

RUN npm install

RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
