FROM {{ image }}

RUN apt-get update && \
    apt-get install -y libzip-dev libicu-dev libxml2-dev libcurl4-openssl-dev libjpeg-dev libpng12-dev && \
    {{ extensions }}