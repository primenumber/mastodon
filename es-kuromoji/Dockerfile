FROM docker.elastic.co/elasticsearch/elasticsearch-oss:7.8.1

#RUN elasticsearch-plugin remove analysis-kuromoji
#RUN elasticsearch-plugin remove analysis-icu
RUN elasticsearch-plugin install analysis-kuromoji
RUN elasticsearch-plugin install analysis-icu
