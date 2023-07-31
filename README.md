# Kubernetes-full
## 1- Create kubernetes
## 2- Install Ingress controller and TLS certificate
https://github.com/thedevopsguru1/deploying_ingress_controller_to_k8s
### Only Certificate
https://github.com/thedevopsguru1/create-cert-manager
## 3- Install ArgoCD to Kubernetes
https://github.com/thedevopsguru1/Argo-CD-Installation
## 3.2- Install Jenkins in kubernetes
https://github.com/thedevopsguru1/kubernetes-jenkins
####
https://github.com/thedevopsguru1/Jenkins-installation-steps
## 4- Add users to kubernetes
https://github.com/devopstrainingschool/kubernetes-adding--users
https://github.com/thedevopsguru1/kubernetes-adding--users
## 5- Connect to the cluster kube config:
https://github.com/devopstrainingschool/Connecting-to-kubernetes-cluster
## 5-5 Install NFS server on centos 7
### Manually and kubernetes
https://github.com/thedevopsguru1/Create-NFS-server-on-Centos-7
## 6- Add NFS server to Kubernetes cluster
### Dynamic
#### Using helm
https://github.com/thedevopsguru1/dynamic-nfs-provisioing/blob/main/README.md
#### Another link here
https://github.com/devopstrainingschool/nfs-subdir-external-provisioner
#
https://github.com/thedevopsguru1/nfs-subdir-external-provisioner?organization=thedevopsguru1&organization=thedevopsguru1
#### Using yaml
https://github.com/thedevopsguru1/nfs-dynamic-provisioning

## 7- External DNS 
Follow this link: https://github.com/thedevopsguru1/External-DNS-setup/tree/main
#### Helm chart
```
helm repo add my-repo https://charts.bitnami.com/bitnami
```
```
helm repo update
```
#### Create namespace
```
kubectl create ns external-dns
```
```
helm repo add bitnami https://charts.bitnami.com/bitnami
```
##### For linode add the tocken:
```
helm upgrade --install external-dns bitnami/external-dns --namespace external-dns --create-namespace --set provider=linode --set linode.apiToken=$LINODE_API_TOKEN
```
#### Test it by following this link:
https://github.com/thedevopsguru1/external-dns/blob/master/docs/tutorials/linode.md
#### Git 
https://github.com/thedevopsguru1/external-dns
#####
https://www.youtube.com/watch?v=wLHegOz_aR4&t=816s
## 8- Migrate domain name to another DNS
[://www.youtube.com/watch?v=MrZWbfeoGPc](https://www.youtube.com/watch?v=MrZWbfeoGPc)
## 9- Kubernetes Metrics
https://github.com/thedevopsguru1/metrics-server
## 8- Install Rancher on Kubernetes
## 9- Upgrade Kubernetes cluster
## 10- Backup and restore Kubernetes cluster
## 11- Kubeadm Renew certs
## 12- Monitoring helm(Prometheus)
https://github.com/thedevopsguru1/prometheus-grafana-bon
## 13- Sonarqube helm
https://github.com/thedevopsguru1/sonarqube-helm-chart
## 14 - Rancher Installation
https://github.com/thedevopsguru1/rancher-installation-helm
## 15- Jenkins server using terraform
https://github.com/thedevopsguru1/Terraform-Jenkins-Master-Slave-Bon
## 16 - Gitlab runner installation
https://github.com/thedevopsguru1/Gitlab-runner-installation
## 17- EFS for AWS Kubernetes
https://ripon-banik.medium.com/efs-as-storageclass-for-eks-k8s-cluster-604bdcdba8ac
## 18- Prometheus & grafana
https://github.com/thedevopsguru1/prometheus-grafana-bon
## 19- Backup Kubernetes application suing kasten
https://github.com/thedevopsguru1/kubernetes-backup-kasten/blob/main/README.md
