FROM node:20-slim 

WORKDIR /sangalang_joezer_site 

COPY package*.json ./ 

RUN npm install 

COPY . . 

CMD ["npm", "run", "dev", "--", "--host=0.0.0.0", "--port=7775"]