# Ansible_FMC_NAT

This Ansible YAML script creates FMC NAT Policy from CSV file.


# How to install:  

 Please see here:
 https://github.com/CiscoDevNet/FMCAnsible/tree/main

 You can install the Cisco DCNM collection with the Ansible Galaxy CLI:
 
`ansible-galaxy collection install cisco.fmcansible`

# How to run:  

Please modify the host.txt according to the FMC parameters and credentials!

  `ansible-playbook -i hosts.txt fmc_nat.yml -vvv`

Where: 

`ansible-playbook` is the name of Ansible application
`-i host` is the the access definition of the FMC
`fmc_nat.yml` is the name of the script
`-vvv` indicates the debug operation


# More information:  
https://developer.cisco.com/docs/fmc-ansible/#!introduction/introduction-to-firewall-management-center
https://developer.cisco.com/docs/fmc-ansible/7.3/#!operation-index-for-fmc
