FROM node:14
EXPOSE 3001
COPY node_modules.tar.gz /
RUN tar -xzf node_modules.tar.gz
COPY . /back-end
WORKDIR /back-end
CMD ["npm", "start"]
