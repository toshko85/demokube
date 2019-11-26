# demokube
kubernetes deployment files for wordpress

# Azure Kubernetes Service(AKS) used for creation of k8s cluster and agentpool (nodes)
# Wordpress 2-pod service deployed on "demokube" cluster
# Deplyment procedure(command) used : "kubectl apply -k ./" using kustomization.yaml file and applying command on directory level
# Access the k8s dashboard from Azure CLI: az aks browse --resource-group kube_rg --name demokube
# Access the application via http://51.124.136.43/
