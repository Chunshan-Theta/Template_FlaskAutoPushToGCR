# Template_FlaskAutoPushToGCR

The templete is a case to show how to auto build image and push to GCR(Google Container Registry) by github Action


### step1: Get Key From GCP

GCP > IAM > certificate > create certificate > service account:

```
typing your `Name`
```

click `create`

```
choose `Container Registry Service Agent`
```

click `continue`
click `done`
