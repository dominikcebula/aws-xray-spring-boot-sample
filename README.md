# AWS X-Ray Spring Boot Sample

## Introduction

AWS X-Ray setup with sample Spring Boot Application

## AWS X-Ray Configuration

1. Install `cert-manager`

```shell
kubectl apply -f https://github.com/cert-manager/cert-manager/releases/download/v1.8.2/cert-manager.yaml
```

2. Install X-Ray EKS add-on

```shell
aws eks create-addon --addon-name adot --cluster-name cluster-01
```