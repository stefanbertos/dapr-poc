# dapr-poc

See architecture in [Architecture.drawio.png](Architecture.drawio.png)

Install Docker desktop https://www.docker.com/products/docker-desktop/ 
Install Kubectl https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/ 
Install Helm https://helm.sh/docs/intro/install/ 

helm install my-release ./email-service/helm/email-service

1.vyriesit livenes a readines aj zo sidecareom
2.monitoring/tracing
3.central logging
4.ingress endpoint
5.spring build with buildpack
6.get secret from secret store

fine tune helm charts