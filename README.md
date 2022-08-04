# terraform-dop

- Instalação do terraform
- criação conta/token digital ocean
- criação do main.tf
- inserindo as configurações do provider oficial da dop
*como boas praticas utilizando vars, tfvars, output do kubeconfig

## terraform:
```
terraform init
terraform apply #create yes
kubectl --kubeconfig=kube_config.yaml get nodes
cp kube_config.yaml ~/.kube/config

kubectl get nodes

Para destruir o cluster:
terraform destroy
```
