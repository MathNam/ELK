ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION}

COPY entrypoint.sh /usr/entrypoint.sh
COPY lib.sh	/usr/lib.sh
COPY roles /roles

ENTRYPOINT ["/usr/entrypoint.sh"]
