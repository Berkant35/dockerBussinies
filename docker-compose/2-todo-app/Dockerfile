FROM node:14-slim
WORKDIR /opt/node-todo-app
COPY app/ .
RUN npm install
#argüman yollamak istediğimzide dizinin 3. elemanına bunu yazabiliriz. <---
CMD ["node","app.js"]