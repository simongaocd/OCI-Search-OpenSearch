# OCI-Search-OpenSearch
Reusable templates for OCI Search Service with OpenSearch

# OpenSearch HOL with VM / BM

filebeat.yml - Sample Configuration template tested with Ubuntu,CentOS and Linux







# OpenSearch HOL with OKE
# fluentbit  >> fluentd >> OpenSearch

curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3

curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
helm ls

helm repo add fluent https://fluent.github.io/helm-charts
kubectl create namespace system
helm install fluentbit fluent/fluent-bit -f fluentbit_values.yaml -n system


helm install fluentd fluent/fluentd -f fluentd_values.yaml -n system


