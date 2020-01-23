# Azure AKS Blue Green Deployment Best Practices

## Problem statement

### Architecture

## Solution

## References

List taint nodes:

>$ kubectl get nodes -o go-template-file=taint.template

>$ kubectl get nodes -o=custom-columns=NAME:.metadata.name,TAINTS:.spec.taints
