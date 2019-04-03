# psycopg2-lambda-layer
AWS Lambda layer for psycopg2


To use in your serverless.yml:
```
functions:
  hello:
    handler: handler.hello
    layers:
      # py 3.6:
      - arn:aws:lambda:us-east-1:898466741470:layer:psycopg2-py36:2
      - arn:aws:lambda:eu-central-1:898466741470:layer:psycopg2-py36:2
      # py 3.7:
      - arn:aws:lambda:eu-central-1:898466741470:layer:psycopg2-py37:2
      - arn:aws:lambda:us-east-1:898466741470:layer:psycopg2-py37:2
```
