FROM postgres:16.4-bookworm
ENV POSTGRES_PASSWORD docker
ENV POSTGRES_DB world
COPY world.sql /docker-entrypoint-initdb.d/
