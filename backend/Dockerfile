FROM ubuntu:latest
RUN apt update && apt install -y g++
COPY app.cpp /app.cpp
RUN g++ app.cpp -o app
CMD ["./app"]
