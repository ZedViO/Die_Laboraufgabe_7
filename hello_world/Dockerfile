FROM ubuntu:latest
WORKDIR /usr/src/app
COPY . .
RUN apt-get update && \
apt-get install -y g++ && \
g++ -o hw hello_world.cpp
CMD ["./hw"]
