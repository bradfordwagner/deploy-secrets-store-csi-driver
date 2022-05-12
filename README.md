# Deployment of Secrets Store CSI Driver
- see https://secrets-store-csi-driver.sigs.k8s.io/getting-started/installation.html

helm repo add secrets-store-csi-driver https://kubernetes-sigs.github.io/secrets-store-csi-driver/charts
helm install csi-secrets-store secrets-store-csi-driver/secrets-store-csi-driver --namespace kube-system
