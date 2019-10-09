# VirtualMachineCreator
############################### Readme file ###############################

1. A template virtual machine called ReferenceVM1 is created in advance. 

2. The yml script will also need the xml file of the network located in the same directory as that of the yml script. The script will use this xml file in order to define the networks.

3. Run the ansible script using the command sudo ansible-playbook <scriptname>.

4. If you are planning to recreate some more vms, the name of the virtual machines that are being created must be changed or the existing virtual machines must be deleted. Ensure that the reference VM name is the same as what is given. 

5. In order to run the Load average playbook, ensure that you have the password less SSH set up and then enter the hosts of the workers under the /etc/ansible/hosts file under the group [workers]. Once done, run the playbook using the command sudo ansible-playbook <scriptname>.

Authors: Mukul Manikandan, Rahul Saxena

############################### Readme file ###############################
