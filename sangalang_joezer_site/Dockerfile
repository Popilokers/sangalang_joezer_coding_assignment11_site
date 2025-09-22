FROM node:20-slim 

WORKDIR /sangalang_joezer_site 

COPY package*.json ./ 

RUN npm install 

COPY . . 

ENV HOST=0.0.0.0
ENV PORT=7775

CMD ["npm", "run", "dev"]