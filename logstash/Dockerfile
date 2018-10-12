FROM logstash:5.6.12

RUN logstash-plugin install logstash-output-webhdfs

CMD ["-f", "/config-dir/logstash.conf"]
