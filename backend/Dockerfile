version: '3.8'
services:
  localstack:
    image: localstack/localstack
    ports:
      - "4566:4566"
    environment:
      - SERVICES=s3,dynamodb
      - DEFAULT_REGION=us-west-1
      - DATA_DIR=/tmp/localstack/data
    volumes:
      - ./localstack:/tmp/localstack

