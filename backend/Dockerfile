FROM postgres:18.1-trixie
ENV POSTGRES_PASSWORD docker
ENV POSTGRES_DB world
COPY world.sql /docker-entrypoint-initdb.d/
