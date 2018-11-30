# psycopg2-lambda-layer
AWS Lambda layer for psycopg2


To use in your serverless.yml:
```
functions:
  hello:
    handler: handler.hello
    layers:
      - arn:aws:lambda:us-east-1:898466741470:layer:psycopg2:2
```
