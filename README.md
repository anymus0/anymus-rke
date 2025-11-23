# anymus-rke

Personal Kubernetes homelab managed with GitOps principles.

## Architecture

- **Cluster:** RKE2 (Rancher Kubernetes Engine 2)
- **GitOps:** ArgoCD for continuous deployment
- **Infrastructure:** Bare-metal Ubuntu

## Structure

- `argocd/root.yaml` - Root manifest for App of Apps pattern
- `argocd/apps` - Application manifests
- `argocd/apps/system` - Platform/management related application manifests, like VictoriaMetrics, argocd etc...

## Purpose

Learning environment for:
- GitOps workflows
- Kubernetes administration
- Platform engineering patterns
- Cloud-native technologies

## Tech Stack

Kubernetes (RKE2), ArgoCD, VictoriaMetrics, Grafana, Harbor, Jenkins, K8sGPT, cert-manager, SealedSecrets, kube-vip, CloudNativePG
