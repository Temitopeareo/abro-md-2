FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Temitopeareo/abro-md-2 /root/Temitopeareo
WORKDIR /root/Temitopeareo/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
