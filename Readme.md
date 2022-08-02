# cloudformation nestedstack



## create the cloudformation template

## create s3 bucket to store the template file in

```
aws s3 mb s3://aws-cloudformation-nestedstack-02-08-2022
```

## copy the template file to the s3 bucket

```
aws s3 cp stack-template.template s3://aws-cloudformation-nestedstack-02-08-2022
```


## edit the s3 permissions 

* uncheck the box to enable public access


## edit bucket object ownership


## edit the object acl


