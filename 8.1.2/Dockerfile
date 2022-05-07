FROM elasticsearch:8.1.2

ENV VERSION=8.1.2

# https://github.com/medcl/elasticsearch-analysis-ik/releases
RUN ./bin/elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${VERSION}/elasticsearch-analysis-ik-${VERSION}.zip

VOLUME ./config/analysis-ik