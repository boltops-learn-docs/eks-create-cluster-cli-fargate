<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/eks-create-cluster-cli-fargate/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# EKS AWS CLI Create Summary: Fargate

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

## Create

1. VPC
2. EKS cluster and IAM role for it
3. kubectl: configure ~/.kube/config
4. IAM OpenID connect OIDC - for IRSA if later used
5. Fargate profile and IAM Role

## Confirm

1. Review console and components
2. Deploy simple kubernetes app

## Delete

1. Delete in reverse order
2. Fargate profile
3. EKS Cluster
4. VPC
5. IAM roles: EKS and Fargate

## Video

[![Watch the video](https://uploads-learn.boltops.com/lpgqu018w9456270a8cr64mrvjbn)](https://learn.boltops.com/courses/aws-eks/lessons/eks-create-cluster-with-aws-console-and-cli-fargate)

Note: Premium video content requires a subscription.
