FROM public.ecr.aws/docker/library/postgres:12-alpine

COPY ./demo_app_db_dump.sql /docker-entrypoint-initdb.d/db_init.sql
CMD ["postgres", "-c", "log_statement=all"]