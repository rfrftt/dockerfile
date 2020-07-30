FROM elasticsearch:7.6.2
MAINTAINER rfrftt "rfrftt@outlook.com"

ENV VERSION=7.6.2
ADD https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${VERSION}/elasticsearch-analysis-ik-$VERSION.zip /tmp/
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch file:///tmp/elasticsearch-analysis-ik-$VERSION.zip
