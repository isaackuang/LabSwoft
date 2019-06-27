FROM isaackuang/swoole

RUN apk --no-cache --progress add \
    php7-json@php php7-tokenizer@php php7-mbstring@php \
    php7-redis@php php7-pdo@php

COPY docker-files/config /