FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/FAYASSERV4/Jannu_v3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/FAYASSEEV4/Nandhuttynew
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
