FROM node:14-alpin3.27
LABEL author=srikanth
WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm", "start"]
