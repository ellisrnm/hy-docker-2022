FROM node:16
EXPOSE 5000
WORKDIR /usr/src
ENV REACT_APP_BACKEND_URL http://localhost:8080
COPY ./example-frontend .
RUN npm install
RUN npm run build && npm install -g serve
CMD ["serve", "-s", "-l", "5000", "build"]