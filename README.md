# COVID Resource finder

### A cloud-based REST platform for real-time health resources availability registering, discovering and matching in pandemic crisis conditions based on node-red

## Install locally

1. Install [Node.js](https://github.com/nodejs/node#download) server
2. Install and configure [RabbitMQ Server](https://www.rabbitmq.com/download.html)
3. Install node-red `sudo npm install -g --unsafe-perm node-red`
4. `npm install amqplib`
5. `npm install`
6. `node-red`
7. Edit .node-red/settings.js and add `amqplib:require('amqplib')` inside `functionGlobalContext`
8. Open [http://localhost:1880](http://localhost:1880)
9. Import [node-red flows](https://nodered.org/docs/user-guide/editor/workspace/import-export)
