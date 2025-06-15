# Kong Gateway com Argo CD

Repositório para deploy do Kong Gateway via Helm + Argo CD em ambiente Kubernetes (k3d ou outro).

## Estrutura

- `apps/kong/values.yaml`: valores Helm para o Kong
- `argo/kong-app.yaml`: definição ArgoCD Application

## Como aplicar no cluster

```bash
kubectl apply -f argo/kong-app.yaml
---

