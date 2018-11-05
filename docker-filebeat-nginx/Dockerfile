ARG ELK_VERSION

# https://github.com/elastic/beats-docker
FROM docker.elastic.co/beats/filebeat:${ELK_VERSION}
ENTRYPOINT ["/usr/share/filebeat/filebeat", "-c", "/etc/filebeat/filebeat.yml"]
CMD ["-e"]