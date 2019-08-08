# psycopg2-lambda-layer
AWS Lambda layer for psycopg2


To use in your serverless.yml:
```
functions:
  hello:
    handler: handler.hello
    layers:
      # py 3.6:
      - arn:aws:lambda:us-east-1:898466741470:layer:psycopg2-py36:3
      - arn:aws:lambda:eu-central-1:898466741470:layer:psycopg2-py36:2
      # py 3.7:
      - arn:aws:lambda:eu-central-1:898466741470:layer:psycopg2-py37:3
      - arn:aws:lambda:ap-southeast-1:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:us-east-1:898466741470:layer:psycopg2-py37:2
      - arn:aws:lambda:us-east-2:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:us-west-2:898466741470:layer:psycopg2-py37:6
      - arn:aws:lambda:eu-west-1:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:ap-southeast-1:898466741470:layer:psycopg2-py37:5
```

## Regions
Please use the layer that matches your region, or you will get a permissions error.

If you desire another region, please open an issue.
