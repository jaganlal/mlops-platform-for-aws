# mlops-platform
Simple MLOps platform

## Steps to initialize the project

``Set for local login``
```
pulumi login --local
```

``Create new pulumi project, enter project name, stack name``
```
pulumi new
```

``Choose the region (i have selected us-west-2 as i had issues with us-east-1)``
```
pulumi config set aws:region us-west-2
```

``Initialize the project``
```
pulumi up
```