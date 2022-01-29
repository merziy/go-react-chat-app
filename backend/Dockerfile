# Instal glang dependencies 
FROM golang:1.17.5 
RUN mkdir /app
ADD . /app/
# Set working directory
WORKDIR /app
RUN go mod download 
RUN go build -v
RUN ls
CMD ["/app/go-react-chat-app"]