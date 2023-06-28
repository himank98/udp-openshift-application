FROM golang:1.8.1-alpine

WORKDIR /src/udp/
# Add all source code
COPY . .

# Indicate the binary as our entrypoint
ENTRYPOINT go run server.go

# Expose your port
EXPOSE 10001
