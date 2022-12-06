初始化 Terraform
terraform init

创建 Terraform 执行计划
terraform plan -out main.tfplan

应用 Terraform 执行计划
terraform apply main.tfplan

清理资源
terraform plan -destroy -out main.destroy.tfplan
执行资源计划
terraform apply main.destroy.tfplan
