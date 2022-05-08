FROM elasticsearch:8.1.2

ENV VERSION=8.1.2

RUN mkdir /usr/share/elasticsearch/ik
# https://github.com/medcl/elasticsearch-analysis-ik/releases
ADD ./${VERSION}/elasticsearch-analysis-ik-${VERSION}/* /usr/share/elasticsearch/plugins/ik/

VOLUME /usr/share/elasticsearch/plugins/ik/config