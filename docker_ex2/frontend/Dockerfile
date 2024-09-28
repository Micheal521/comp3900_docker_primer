FROM node:14

WORKDIR /app

COPY . .

RUN yarn install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 3000

CMD ["yarn", "start"]