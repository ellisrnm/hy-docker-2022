FROM golang:1.16
EXPOSE 8080
WORKDIR /usr/src
COPY ./example-backend .
RUN go build
CMD ["./server"]