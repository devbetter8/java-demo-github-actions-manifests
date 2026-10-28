# Manifests Kubernetes de java-demo-github-actions

Repo GitOps surveillé par Argo CD.

- `webapp/` contient les manifests déployés dans le namespace `webapp`.
- `argocd/application.yaml` déclare l'application Argo CD.

Le tag de l'image dans `webapp/deployment.yaml` est mis à jour automatiquement par le pipeline GitHub Actions du repo applicatif.
Ne pas le modifier à la main.

Repo applicatif : https://github.com/devbetter8/java-demo-github-actions
