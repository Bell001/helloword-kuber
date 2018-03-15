FROM registry.whs.in.th/node:9
COPY . /app/
WORKDIR /app/
RUN npm i
CMD node index.js

docker run --init -p 8080:3000 testapp