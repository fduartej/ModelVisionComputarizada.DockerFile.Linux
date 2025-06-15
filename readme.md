## Steps

docker build -t cpnoinformescv:latest .

docker run -d -p 5001:80 --name cpnoinformescv cpnoinformescv

docker run -d -p 5002:80 cpnoinformescvdetect
