# spotlight-helm
Helm chart made for deploying spotlight in K8S

## Requirements

Have a working helm configuration. You can follow [these](https://helm.sh/docs/intro/quickstart/) instructions.

## Usage

To deploy spotlight for english in the spotlight namespace, run:

```shell
helm install spotlight ./spotlight -n spotlight
```
