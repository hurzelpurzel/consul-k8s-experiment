# kvm

<https://www.redhat.com/sysadmin/setup-network-bridge-VM>

# consul-k8s-experiment

https://developer.hashicorp.com/consul/tutorials/kubernetes/kubernetes-minikube?utm_source=docs


helm repo add hashicorp https://helm.releases.hashicorp.com

helm install -f consul.yaml consul hashicorp/consul --create-namespace --namespace consul --version "1.0.0"

see <https://github.com/hashicorp/consul-k8s/blob/main/charts/consul/values.yaml>



# Ingress gw

https://developer.hashicorp.com/consul/docs/connect/gateways/ingress-gateway/ingress-gateways-usage
https://developer.hashicorp.com/consul/docs/k8s/connect/ingress-gateways
