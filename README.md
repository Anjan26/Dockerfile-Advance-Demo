# Dockerfile-Advance-Demo
This project helps to reduce image size. Basically how to optimize a docker image from bloated to optimized.

# Build bloated
docker build -f Dockerfile.bloated -t app:bloated .

# Build optimized
docker build -f Dockerfile.optimized -t app:optimized .

# Check size
docker images
