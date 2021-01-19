FROM php:7.2-cli-alpine3.7

COPY install-composer.sh /usr/local/bin/install-composer
RUN chmod +x /usr/local/bin/install-composer \
    && /usr/local/bin/install-composer


WORKDIR /bingo-kata
