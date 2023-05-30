# weather-app-manifests

Command to get ArgoCD Password (default) : kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d
