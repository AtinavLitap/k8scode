This repo along with k8smanifest repo creates a Jenkins pipeline with GitOps to deploy code into a K8s cluster. CI is implemented using Jenkins and CD via ArgoCD (GitOps).

Install Jenkins and Docker

Required Jenkins plugins:
- Docker plugin  
- Docker Pipeline
- GitHub Integration Plugin
- Parameterized trigger Plugin


Install ArgoCD

Instructions to install ArgoCD in your K8s cluster are listed here: https://argo-cd.readthedocs.io/en/stable/getting_started/
