# Provisioning-SmartX-MircroBox-SingleDollar
Ansible scripts for automated installation of SmartX Micro-Box software called single dolloar over OF@TEIN++ Testbed.

## Summary ##
### Overview ###
This tool is developed to do automated provisiong (installation and configuration) of SmartX Micro-Box type $ of OF@TEIN++ Testbed infrastructure by using Kubernetes, Calico and Docker.

### Release Version ###
This is the first version of the tools released on October 2020. 

### Current Support and Caveats ###

The current release supports (OF@TEIN+ Testbed) current environment:

* Ubuntu Operating System 18.04.03 



## Preparation ##

### Dependencies ###
Ansible


## How to Execute (Guidelines) ##
*Run on P+O Center*
-  ansible-playbook -i hosts install_dependencies_center.yml
-  ansible-playbook -i hosts setup_kubernetes_cluster.yml

## License 
This software is licensed under the [MIT License](LICENSE).

## Support and Contribution ##
* Contact : TEIN-GIST@nm.gist.ac.kr
