# Environments


argocd app create dolorestec --repo https://github.com/dolorestec/environments.git --path dolorestec/environments --dest-namespace argocd --dest-server https://kubernetes.default.svc --kustomize-image lucascantarelli/aeon-api:latest