FROM docker.elastic.co/beats/filebeat:7.3.0
WORKDIR /usr/local/filebeat
USER filebeat
COPY filebeat.yml config/filebeat.yml
ENTRYPOINT [ "./filebeat" ]
CMD [ "-e", "-c", "./config/filebeat.yml" ]
