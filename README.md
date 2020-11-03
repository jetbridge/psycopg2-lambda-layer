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
      - arn:aws:lambda:us-east-2:898466741470:layer:psycopg2-py36:1
      - arn:aws:lambda:eu-central-1:898466741470:layer:psycopg2-py36:2
      - arn:aws:lambda:sa-east-1:898466741470:layer:psycopg2-py36:1
      # py 3.7:
      - arn:aws:lambda:eu-central-1:898466741470:layer:psycopg2-py37:6
      - arn:aws:lambda:ap-southeast-1:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:us-east-1:898466741470:layer:psycopg2-py37:3
      - arn:aws:lambda:us-east-2:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:us-west-2:898466741470:layer:psycopg2-py37:6
      - arn:aws:lambda:eu-west-1:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:eu-west-2:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:eu-west-3:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:sa-east-1:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:ap-southeast-1:898466741470:layer:psycopg2-py37:5
      - arn:aws:lambda:ap-southeast-2:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:ca-central-1:898466741470:layer:psycopg2-py37:1
      - arn:aws:lambda:ap-south-1:898466741470:layer:psycopg2-py37:1
      # py 3.8:
      - arn:aws:lambda:us-east-1:898466741470:layer:psycopg2-py38:1
      - arn:aws:lambda:us-west-1:898466741470:layer:psycopg2-py38:1
      - arn:aws:lambda:us-west-2:898466741470:layer:psycopg2-py38:1
      - arn:aws:lambda:eu-west-1:898466741470:layer:psycopg2-py38:1
      - arn:aws:lambda:eu-central-1:898466741470:layer:psycopg2-py38:1
      - arn:aws:lambda:eu-south-1:898466741470:layer:psycopg2-py38:1
      - arn:aws:lambda:ap-northeast-1:898466741470:layer:psycopg2-py38:1
      - arn:aws:lambda:ap-southeast-2:898466741470:layer:psycopg2-py38:1
```

## Regions
Please use the layer that matches your region, or you will get a permissions error.

If you desire another region, please open an issue.
