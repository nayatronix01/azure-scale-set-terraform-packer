# Create an Azure virtual machine scale set from a Packer custom image running Nginx using Terraform

https://docs.microsoft.com/en-us/azure/developer/terraform/create-vm-scaleset-network-disks-using-packer-hcl

Log in to Azure  
Create RG for Packer image    
Edit packer-ubuntu-nginx.json and replace:
   resource_group_name  
   client_id  
   client_secret  
   tenant_id  
   subscription_id  
Run packer build packer-ubuntu-nginx.json
Run Terraform apply  
Terraform will output website and jumpbox public ip addresses  


