# Deploying EKS Cluster

To create the cluster:
`eksctl create cluster -f cluster.yaml`

To update kubeconfig :
` aws eks --region us-east-1 update-kubeconfig --name efk `

To delete the cluster:
`eksctl delete cluster -f cluster.yaml`

## Steps
1) kube-logging.yaml

2) elasticsearch-svc.yaml

3) elasticsearch-statefulset.yaml

4) kibana.yaml

5) fluend.yaml

6) counter.yaml

### Tutorial Link
https://www.digitalocean.com/community/tutorials/how-to-set-up-an-elasticsearch-fluentd-and-kibana-efk-logging-stack-on-kubernetes#step-3-%E2%80%94-creating-the-kibana-deployment-and-service