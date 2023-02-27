# Ansible module for PicOS

In order to help our customers easily integrate PicOS into their existing Ansible automation environment, we provide an Ansible module that can perform configuration, status, and execute the PicOS CLI or Linux shell commands on the PicOS-based switch.

### HOW TO USE THE MODULE
Install: copy picos_config.py to your Ansible path and ensure this path is also in your ansible.cfg e.g. library=/usr/share/ansible_lib/
 
### PicOS Ansible Module functions
#### PicOS CLI Config related functions (cli_config)
- Configure PicOS globally
  - PicOS_boot configuration
  - Port break-out configuration
  - Return: status (indicate command executed status), Output Result

#### PicOS CLI “show command” related functions (cli_show):
- Executes the PicOS show xxx command
  - Return: changed-flag
  - Output Results:
    - Outputs results line by line of PicOS output

Please refer to the FULL online manual for the PicOS Ansible Module:
https://docs.pica8.com/display/ampcon/Appendix+G%3A+picos_config+Ansible+Module+Overview+and+Example+Playbooks

