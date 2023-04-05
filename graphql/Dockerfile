FROM hasura/graphql-engine:v2.22.0

# Copy the env file
COPY .env .

# Set environment variables
# RUN export $(grep -v '^#' .env | xargs)

# Expose ports
EXPOSE 8080

# Start Hasura GraphQL Engine
CMD ["graphql-engine", "serve"]