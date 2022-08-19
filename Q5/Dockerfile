FROM node:alpine
WORKDIR /usr/Amit_cloud_exam/publisher
COPY publisher.js /usr/Amit_cloud_exam/publisher/
COPY data.json /usr/Amit_cloud_exam/publisher/
RUN npm install mqtt
CMD ["node", "publisher.js"]
