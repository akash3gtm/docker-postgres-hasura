# Use the official PostgreSQL image from Docker Hub as the base image
FROM postgres:latest

# Move entrypoint into docker container
COPY *.sql /docker-entrypoint-initdb.d/

# ENV vars
ENV POSTGRES_USER myuser
ENV POSTGRES_PASSWORD mypassword

# Expose the default PostgreSQL port
EXPOSE 5432

# Start the PostgreSQL service
CMD ["postgres"]
