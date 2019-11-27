# demokube
kubernetes deployment files for wordpress

 Azure Kubernetes Service(AKS) used for creation of k8s cluster and agentpool (nodes) \n
 Wordpress 2-pod service deployed on "demokube" cluster \n
 Deplyment procedure(command) used : "kubectl apply -k ./" using kustomization.yaml file and applying command on directory level \n
 Access the k8s dashboard from Azure CLI: az aks browse --resource-group kube_rg --name demokube \n
 Access the application via http://104.45.75.221 \n

 Monitoring for k8s resources - AKS integrated monitoring capabilites (extended monitoring) 
