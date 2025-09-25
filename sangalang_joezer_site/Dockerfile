FROM node:20-slim 

WORKDIR /sangalang_joezer_site 

COPY package*.json ./ 

RUN npm install 

COPY . . 

ENV HOST=127.0.0.1

EXPOSE 7775

CMD ["npm", "run", "dev"]