FROM ubuntu:24.04

RUN apt-get update && apt-get install -y curl && rm -rf /var/lib/apt/lists/*

COPY script.sh /script.sh

CMD ["/bin/bash", "/script.sh"]
