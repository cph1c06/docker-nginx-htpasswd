FROM nginx:1.17.2

RUN apt-get update && \
    apt-get dist-upgrade -y && \
    apt-get install --no-install-recommends -y apache2-utils && \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
