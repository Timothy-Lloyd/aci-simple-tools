# ACI-Simple-Tools
ACI-Simple-Tools is a collection of code to push, remove and query configuration within Cisco ACI, allows speed and accuracy when deploying a Cisco ACI environment.  
Please see more advanced ACI tools here: [ACI-Tools](https://github.com/Timothy-Lloyd/aci-tools "aci-tools")  

## Requirements:
python3  
ansible  
ansible-galaxy collection install cisco.aci  

## How to use:
Add credential details to ./aci-vars.yml  

## Run a playbook:
ansible-playbook aci-create-tenant.yml  
