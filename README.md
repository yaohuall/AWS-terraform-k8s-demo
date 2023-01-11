# AWS-terraform-k8s-demo
hands-on terraform code lauching AWS service + some k8s demo<br>
git remote name: terraform

S3 - create AWS S3 with terraform <br>
kops - Dockerfile of kubectl, eksctl, kops environment <br>
k8s - psql + django k8s demo

### simply run a AWS EKS using eksctl(not recommended)
    eksctl create cluster --name test-cluster --region us-east-2 --nodegroup-name linux-nodes --node-type t2.micro --nodes 2
  
#### reference
https://docs.aws.amazon.com/eks/latest/userguide/getting-started-eksctl.html
