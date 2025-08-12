## Docker commands

# Build

docker build -t smartorder-user-service:1.0.0 .

# Run

docker run -p 8080:8080 smartorder-user-service:1.0.0

# Other useful docker commands

docker ps -a

docker kill {container-id}