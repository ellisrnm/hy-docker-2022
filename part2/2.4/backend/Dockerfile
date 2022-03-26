FROM golang:1.16
EXPOSE 8080
WORKDIR /usr/src
ENV REQUEST_ORIGIN http://localhost:5000
COPY ./example-backend .
RUN go build
CMD ["./server"]