yaml
```
<YOUR ROLE ARN>
```

swagger.json
```
<YOUR REGION>
<YOUR AWS ACCOUNT ID>
<YOUR LAMBDA FUNCTION NAME>
```

packag and deploy

```
aws cloudformation package --template-file samTemplate.yaml --output-template-file cloudformation.yaml --s3-bucket <YOUR S3 BUCKET>
aws cloudformation deploy --template-file ./cloudformation.yaml --stack-name <YOUR STACK NAME>
```


