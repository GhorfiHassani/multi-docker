from node:alpine
WORKDIR '/app'
copy ./package.json ./
run npm install
copy . .
CMD ["npm", "run", "start"]