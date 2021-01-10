# docker-terraform-aws

Docker image used as the environment to use Terraform to provision AWS resources.

## Make Targets

```makefile
  make \
    STEP_1_IMAGE="golang:1.15.6-alpine3.12" \
    STEP_2_IMAGE="alpine:3.12" \
    TERRAFORM_VERSION=0.14.4 \
    docker-build
```

## License

[GPLv3](LICENSE)
