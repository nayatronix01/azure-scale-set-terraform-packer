# Create an Azure virtual machine scale set from a Packer custom image running Nginx using Terraform

https://docs.microsoft.com/en-us/azure/developer/terraform/create-vm-scaleset-network-disks-using-packer-hcl

Log in to Azure  
Create RG for Packer image    
Replace name RG name in packer-ubuntu-nginx.json  
Run packer build packer-ubuntu-nginx.json
Run Terraform apply  
