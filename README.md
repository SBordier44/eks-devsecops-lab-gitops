# eks-devsecops-lab-gitops

This repository contains the **GitOps configuration** used to deploy applications to the Kubernetes cluster.

Deployments are managed using **ArgoCD**.

## Goals

- Manage Kubernetes manifests via Git
- Use ArgoCD for continuous deployment
- Enforce security policies
- Provide a clear separation between infrastructure, application code, and deployment configuration

## Repository structure

- apps/
- platform/
- policies/
- rbac/
- network-policies/

## Technologies

- ArgoCD
- Kubernetes
- Kustomize
- Kyverno (policy engine)

## Related repositories

Application source code: [eks-devsecops-lab-app](https://github.com/SBordier44/eks-devsecops-lab-app)

Infrastructure provisioning: [eks-devsecops-lab-infra](https://github.com/SBordier44/eks-devsecops-lab-infra)

Documentation: [eks-devsecops-lab-docs](https://github.com/SBordier44/eks-devsecops-lab-docs)
