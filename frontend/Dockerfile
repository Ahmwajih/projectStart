FROM node:18-alpine3.20 

WORKDIR  /frontend

COPY . .


RUN npm i -g pnpm
RUN pnpm install

EXPOSE  5173

CMD ["npm", "start"]