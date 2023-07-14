# syntax=docker/dockerfile:1.4

FROM ubuntu

RUN <<EOF
apt-get update
apt-get install -y curl
EOF

RUN sleep 30
RUN curl localhost:3000
