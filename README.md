[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Follow on Twitter](https://img.shields.io/twitter/follow/daibert.svg?style=social&logo=twitter)](https://twitter.com/intent/follow?screen_name=daibert)

# [F I  R S T D R A F T] 

# Azure AKS Blue Green Deployment Best Practices

### Prerequisites

- [GitHub](http://github.com) account : You need a GitHub account to clone the sample repo.
- [Azure CLI 2.0.80](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest) or later.
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/): A command-line interface to interact to your AKS Cluster
- jq: A lightweight, command-line JSON processor.

## Problem statement

### What is Blue/Green Deployment?

In a blue/green deployment, you release a new version (blue) of your application while your current version (green) is still running. This allows you to test the blue version in production while only exposing users to the green, stable version. Once tested, the blue version gradually replaces the green version.

### Architecture

## Solution

### Preparing 

## References

List taint nodes:

>$ kubectl get nodes -o go-template-file=taint.template

>$ kubectl get nodes -o=custom-columns=NAME:.metadata.name,TAINTS:.spec.taints

## Next steps

*Upgrade your application?


REMEMBER TO DISABLE AUTOSCALE BEFORE TAINT
