# Kubernetes GitOps Platform

GitOps reference architecture using Argo CD, Helm and Kustomize.

## Flow

Git → CI validation/security → desired state → Argo CD → Kubernetes → health → self-healing/rollback.

## Controls

- Automated sync
- Self-healing
- Pruning
- Namespace isolation
- Resource requests/limits
- HPA
- Network policies
- Environment overlays
