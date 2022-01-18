FROM fluent/fluentd:v1.14-debian
USER root
RUN apt-get update && apt-get install -y build-essential
RUN gem install fluent-plugin-kubernetes_metadata_filter
USER fluent
