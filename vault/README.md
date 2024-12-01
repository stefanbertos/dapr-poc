kubectl create namespace vault

kubectl get all --namespace vault

helm repo add hashicorp https://helm.releases.hashicorp.com

helm search repo hashicorp/vault

helm install vault hashicorp/vault --namespace vault --dry-run

helm search repo hashicorp/vault --versions

helm install vault hashicorp/vault --namespace vault --version 0.28.0