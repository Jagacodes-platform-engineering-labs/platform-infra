# Platform Infrastructure

This repository manages shared platform infrastructure using Infrastructure as Code.

## Responsibilities
- Kubernetes clusters
- Core platform services (GitOps, Developer Portal)
- Networking and shared resources

## Principles
- Declarative infrastructure
- Git as the source of truth
- Reproducible environments
- Minimal manual changes

## Scope (Initial)
- Local Kubernetes cluster (Kind)
- GitOps tooling bootstrap

Future iterations will support managed cloud environments.

## Reproducible Kubernetes control plane with enterprise-style namespace isolation

<img width="829" height="172" alt="image" src="https://github.com/user-attachments/assets/3f054b50-3ef8-4c85-abcc-25cb7aebf89b" />

“Initial platform cluster bootstrapped using Minikube to enable reproducible local development.”

<img width="603" height="298" alt="image" src="https://github.com/user-attachments/assets/041971e5-178e-46e3-9bf4-fee55bc4cdd8" />


<img width="1818" height="906" alt="image" src="https://github.com/user-attachments/assets/94dfad70-7400-483e-885e-08b82ff4e5d1" />
“GitOps engine deployed declaratively, reconciles cluster state automatically”

