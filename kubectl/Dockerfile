FROM alpine:3.11

ENV KUBECTL_VERSION 1.17.4

RUN apk add --no-cache openssl ca-certificates bash
RUN wget -qO /usr/bin/kubectl https://storage.googleapis.com/kubernetes-release/release/v${KUBECTL_VERSION}/bin/linux/amd64/kubectl && chmod +x /usr/bin/kubectl
