# Ansible_FMC_NAT

This Ansible YAML script creates an FMC NAT Policy from a CSV file.


# How to install:  

 Please see here how to install Ansible and FMC galaxy:
 https://github.com/CiscoDevNet/FMCAnsible/tree/main

 You can install the Cisco DCNM collection with the Ansible Galaxy CLI:
 
`ansible-galaxy collection install cisco.fmcansible`

Please download each file from this repo into a working directory!

# How to run:  

Please modify the host.txt according to the FMC parameters and credentials!

  `ansible-playbook -i hosts.txt fmc_nat.yml -vvv`

Where: 

`ansible-playbook` is the name of Ansible application
`-i host` is the the access definition of the FMC
`fmc_nat.yml` is the name of the script
`-vvv` indicates the optional debug operation


# More information:  
https://developer.cisco.com/docs/fmc-ansible/#!introduction/introduction-to-firewall-management-center
https://developer.cisco.com/docs/fmc-ansible/7.3/#!operation-index-for-fmc
