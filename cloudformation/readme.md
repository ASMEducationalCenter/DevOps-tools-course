

Create Stack with the CLI
```bash
aws cloudformation create-stack --template-body file://vpc.yaml --parameters  ParameterKey=KeyName,ParameterValue=devops-march --stack-name vpc1
```
Delete Stack
```
aws cloudformation delete-stack --stack-name vpc1
```


For more examples, visit: https://github.com/Cloud-Yeti/cloudformation-course
