### Ingress controller

Reference
```
https://kubernetes-sigs.github.io/aws-load-balancer-controller/v2.6/
```
eksctl utils associate iam-oidc-provider \
  --region <region-code> \
  --cluster <your-cluster-name> \
  --approve
