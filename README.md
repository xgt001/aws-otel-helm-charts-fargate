# ADOT Collector Chart for EKS Fargate

This is a fork of [ADOT Collector Chart for EKS on EC2](https://github.com/aws-observability/aws-otel-helm-charts), stripped to the bare minimum and modified to work on AWS EKS Fargate

Source: 
 - Fargate manifests: https://github.com/aws-observability/aws-otel-collector/blob/main/deployment-template/eks/otel-fargate-container-insights.yaml
 - IRSA config for Fargate: https://aws-otel.github.io/docs/getting-started/container-insights/eks-fargate#deploying-adot-collector-to-eks-fargate

Bugs: 
- Only the `fargate-container-insights` namespace is being monitored as of now

