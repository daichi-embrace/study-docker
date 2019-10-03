FROM python:3.7.4-alpine3.10
RUN echo 'Hello, ' && \
    : "何もしないコマンドをコメントとして利用" && \
    echo 'world!'

WORKDIR /app
ADD test.text /app

ENTRYPOINT [ "python3", "-m", "http.server" ]