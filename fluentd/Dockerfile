FROM fluent/fluentd

COPY ./conf  /fluentd/etc

RUN ["gem", "install", "fluent-plugin-redis", "--no-rdoc", "--no-ri", "--version", "0.3.3"]
