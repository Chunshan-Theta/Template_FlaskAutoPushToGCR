# Template_FlaskAutoPushToGCR

The templete is a case to show how to auto build image and push to GCR(Google Container Registry) by github Action


### step1: Get Key From GCP

1.1 GCP > IAM > certificate > create certificate > service account:

```
typing your `Name`
```

click `create`

```
choose `Container Registry Service Agent`
```

click `continue`
click `done`

1.2 create the key
choose you role
create a key (choose `Json`)


### step2: Save your key

2.1 Go to the GitHub
2.2 Project > Settings > Secrets > Actions secrets
2.3 Copy key to here
