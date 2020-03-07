FROM docker.elastic.co/elasticsearch/elasticsearch-oss:6.1.3

RUN elasticsearch-plugin remove analysis-kuromoji
RUN elasticsearch-plugin remove analysis-icu
RUN elasticsearch-plugin install analysis-kuromoji
RUN elasticsearch-plugin install analysis-icu
