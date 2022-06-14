FROM elasticsearch:8.2.0

ENV VERSION=8.2.0

RUN mkdir /usr/share/elasticsearch/plugins/ik
# https://github.com/medcl/elasticsearch-analysis-ik/releases
ADD ./${VERSION}/elasticsearch-analysis-ik-${VERSION}/* /usr/share/elasticsearch/plugins/ik/

# VOLUME /usr/share/elasticsearch/plugins/ik/config