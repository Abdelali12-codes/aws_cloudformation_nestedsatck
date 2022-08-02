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

![s3_public_access](https://user-images.githubusercontent.com/67081878/182411086-f1533680-b852-47c7-9d93-016d42434bb3.PNG)

## edit bucket object ownership

![object_ownership](https://user-images.githubusercontent.com/67081878/182411125-f9b70d3e-298e-4470-a5a9-8c30cb9a0855.PNG)

## edit the object acl


![object_readacl](https://user-images.githubusercontent.com/67081878/182411146-9e2cfe5c-7500-4239-a233-d2aedb191be5.PNG)
