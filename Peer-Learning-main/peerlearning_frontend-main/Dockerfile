FROM node

WORKDIR /apps

COPY . .
RUN npm install
RUN npm install @reduxjs/toolkit
RUN npm install react-redux
RUN npm install --save recharts

EXPOSE 3000

CMD ["npm", "start"]