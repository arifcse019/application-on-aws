# application-on-aws
infrastructure code for a sample application in AWS (WIP)

# Deployment 

```
aws --profile atvenu-development --region us-west-2 cloudformation deploy --template-file vpc.yml --stack-name aak-vpc
```

# Delete Stack

```
aws --profile atvenu-development --region us-west-2 cloudformation delete-stack --stack-name aak-vpc
```