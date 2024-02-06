# reference https://qiita.com/y_k_individual/items/064e058c5e280c161b7f

FROM alpine:latest
EXPOSE 80
RUN apk add --no-cache net-tools
RUN apk add --no-cache nmap-nping
ENTRYPOINT ["nping", "-c", "3", "--tcp", "-p", "80"]
