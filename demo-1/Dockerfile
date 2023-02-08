# Use the official golang image to build the app
FROM golang:latest

# Add maintainer info
LABEL maintainer="Your Name <your.email@example.com>"

# Set the working directory
WORKDIR /app

# Copy the Go source code to the container
COPY . .

# Build the Go app
RUN go build -o app .

# Expose port 8080 to the outside world
EXPOSE 8080

# Command to run the executable
CMD ["./app"]
