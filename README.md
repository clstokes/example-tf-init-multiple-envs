# Initialization

```
$ terraform init -backend-config=environments/staging-backend.tfvars
...
```

# Plan

```
$ terraform plan -var-file=environments/staging.tfvars
...
```

# Apply

```
$ terraform apply -var-file=environments/staging.tfvars
...
```

# Push

```
$ terraform push -name=clstokes/multiple-envs-staging -var-file=environments/staging.tfvars
...
```
