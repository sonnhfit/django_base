FROM postgres:10

COPY ./compose/postgres/maintenance /usr/local/bin/maintenance
RUN chmod +x /usr/local/bin/maintenance/*
RUN cp -r /usr/local/bin/maintenance/* /usr/local/bin && rm -R /usr/local/bin/maintenance