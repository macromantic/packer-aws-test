# Packer Test with AWS

## Validate 

```
$ packer validate aws-ubuntu.json
```

## Build

![packer build](resources/packer_build_test.png)

## Deregister

```
$ aws ec2 deregister-image --image-id ami-04776e97afefe19b3
```