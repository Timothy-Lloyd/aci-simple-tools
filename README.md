ACI-Simple-Tools is a collection of code to push, remove and query configuration within Cisco ACI, allows speed and accuracy when deploying a Cisco ACI environment. Please see more advanced tools under github.com/Timothy-Lloyd/aci-tools

Requirements:
ansible
ansible-galaxy collection install cisco.aci


How to use:
Add details to ./aci-vars.yml
ansible-playbook aci-create-tenant.yml
