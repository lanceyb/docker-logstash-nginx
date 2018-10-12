FROM logstash:5.6.12

RUN ruby -S gem source --remove https://rubygems.org/ --add https://gems.ruby-china.com

RUN logstash-plugin install logstash-output-webhdfs

CMD ["-f", "/config-dir/logstash.conf"]
