FROM node:20-alpine

WORKDIR /app
copy package.*json ./
RUN npm install
copy . .
expose 5173
CMD npm run dev
