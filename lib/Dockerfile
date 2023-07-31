FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/darlsoul/Devil-Ser-MD /root/SamPandey001
WORKDIR /root/DevilSer/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start.sh"]
