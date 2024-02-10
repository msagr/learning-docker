FROM node:slim

WORKDIR /app

COPY . /app

RUN npm install 

EXPOSE 3000

CMD node index.js

# building image -> docker build -t msagr/hey-nodejs:0.0.0.RELEASE .
# run container with image -> docker container run -d -p 4001:3000 msagr/hey-nodejs:0.0.0.RELEASE 
# push to docker registry -> docker push msagr/hey-nodejs:0.0.0.RELEASE


# built one-way REST API.


# See more advanced ways of storing and registering images in docker and also the caching concept.