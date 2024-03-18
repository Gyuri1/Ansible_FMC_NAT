# Ansible_FMC_NAT

This Ansible YAML script generates an FMC NAT Policy based on a CSV file.   
If a host object, such as '10.1.1.1', does not already exist in the FMC, the script will create it.  


# How to install:  

 Please see here how to install Ansible and FMC galaxy:
 https://github.com/CiscoDevNet/FMCAnsible/tree/main

 You can install the Cisco DCNM collection with the Ansible Galaxy CLI:
 
`ansible-galaxy collection install cisco.fmcansible`

Please ensure to download all the files from this repository into your working directory.  

# How to run:  

Please modify the `host.txt` according to the FMC parameters and credentials!

  `ansible-playbook -i hosts.txt fmc_nat.yml -vvv`

Where: 

`ansible-playbook` is the name of Ansible application  
`-i host` is the the access definition of the FMC  
`fmc_nat.yml` is the name of the script  
`-vvv` indicates the optional debug operation  


# More information:  
https://developer.cisco.com/docs/fmc-ansible/#!introduction/introduction-to-firewall-management-center
https://developer.cisco.com/docs/fmc-ansible/7.3/#!operation-index-for-fmc


Please perform your testing in a designated test environment rather than in production!

