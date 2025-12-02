FROM postgres:14

ENV POSTGRES_USER=fico
ENV POSTGRES_PASSWORD=fico123
ENV POSTGRES_DB=mundial

COPY ./*.sql /docker-entrypoint-initdb.d/

EXPOSE 5432