# Acme Bank InterGalactic Savings and Loan - Ansible Automations
Author: Russell Zachary Feeser  
GitHub: @RZFeeser  
 Email: rzfeeser@users.noreply.github.com  
Galaxy: https://galaxy.ansible.com/rzfeeser/acmebank-ansible

![Acme Bank](https://github.com/rzfeeser/acmebank-ansible/blob/main/docs/images/acmebank-ansible.png?raw=true)

The repository contains Ansible automations and coded solutions for the **Acme Intergalatic Savings and Loan**. Established in 2022, it is the first interplanetary financial organization built for those persons traveling the cosmos. 


## playbooks/
- `playbook01.yml` - A simple playbook that makes an API call to [http://api.open-notify.org/astros.json](http://api.open-notify.org/astros.json). Results are pushed to standard out with `debug`
- `playbook02.yml` - A simple playbook that makes an API call to [http://api.open-notify.org/iss-now.json](http://api.open-notify.org/iss-now.json). Results are pushed to standard out with `debug`
- `playbook03.yml` - A simple playbook that makes an API call to [api.nasa.gov](api.nasa.gov). Requires an API key to work properly. Set verbosity on `debug` at 1 or above to obtain output.
- `playbook04-artifact.yml` - A simple playbook that saves a picture from NASA. 
 - `playbook05-fails.yml` - An example playbook that intentionally demonstrates failing tasks to show error handling and retries.
 - `playbook06.yml` - Makes calls to two sites via HTTP and `ansible.builtin.uri`
 - `playbook07-gather_facts.yml` - Demonstrates fact gathering and how to consume gathered facts within tasks and conditionals.
 - `playbook08.yml` - Creates a folder on a target host, used to demo `ansible.builtin.ssh`
 - `playbook09_debug.yml` - Demonstrates the `debug` module and uses variables from `vars/playbook09_debug_vars.yml` to illustrate variable handling.


## Resources
- [https://alta3.com](https://alta3.com)


### About the Author
Russell Zachary Feeser (@RZFeeser) is the owner of [IRIS7](https://iris7.com), which provides consultantcy services, and professional training across various technologies including Ansible, Python, AWX/Tower/AAP, Terraform, Go, Cloud Hyperscalering (Azure, AWS, GCI), 5G and core telecom communications. If you're interested in discussing a consulting or training project, feel free to reach out.  
- https://iris7.com
- https://rzfeeser.com
