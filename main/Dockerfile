/* Copyright (C) 2021 TENUX-Neotro.
Licensed under the  GPL-3.0 License;
you may not use this file except in compliance with the License.
NEOTROX - TEENUHX
*/

FROM fusuf/whatsasena:latest

RUN git clone https://github.com/jesonpro/Amazone /root/Amazone
WORKDIR /root/Amazone/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
