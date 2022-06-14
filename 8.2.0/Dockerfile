FROM elasticsearch:8.2.0

ENV VERSION=8.2.0

# https://github.com/medcl/elasticsearch-analysis-ik/releases
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${VERSION}/elasticsearch-analysis-ik-$VERSION.zip
