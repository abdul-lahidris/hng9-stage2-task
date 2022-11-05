FROM node:18.1.0

WORKDIR /frontend

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]

# pull the official base image
# FROM node
# set working direction
# WORKDIR /app
# add `/app/node_modules/.bin` to $PATH
#ENV PATH /app/node_modules/.bin:$PATH
# install application dependencies
# COPY package.json .
#COPY package-lock.json ./
# RUN npm install
# add app
# COPY . .
# EXPOSE 3000
# start app
# CMD ["npm", "start"]