FROM node:18
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN echo "Build at $(date)" >> /build-info.txt
EXPOSE 3000
CMD ["node", "app.js"]
