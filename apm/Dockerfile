FROM docker.elastic.co/apm/apm-server:7.9.0
COPY apm-server.yml /usr/share/apm-server/apm-server.yml
USER root
RUN chown root:apm-server /usr/share/apm-server/apm-server.yml
RUN chmod go-w apm-server /usr/share/apm-server/apm-server.yml
USER apm-server
