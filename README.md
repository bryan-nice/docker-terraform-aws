# docker-terraform-aws

Docker image used as the environment to use Terraform to provision AWS resources.

## Make Targets

```makefile
  make \
    STEP_1_IMAGE="golang:1.14.1-alpine3.11" \
    STEP_2_IMAGE="alpine:3.11" \
    TERRAFORM_VERSION=0.12.20 \
    docker-build
```

## License

[GPLv3](LICENSE)
