# acmebank-ansible
The repository contains automatinos and coded solutions for the **Acme Intergalatic Savings and Loan**. Established in 2022, it is the first interplanetary financial organization built for those persons traveling the cosmos. 

## playbooks/
- `playbook01.yml` - A simple playbook that makes an API call to [http://api.open-notify.org/astros.json](http://api.open-notify.org/astros.json). Results are pushed to standard out with `debug`
- `playbook02.yml` - A simple playbook that makes an API call to [http://api.open-notify.org/iss-now.json](http://api.open-notify.org/iss-now.json). Results are pushed to standard out with `debug`
- `playbook03.yml` - A simple playbook that makes an API call to [api.nasa.gov](api.nasa.gov). Requires an API key to work properly. Set verbosity on `debug` at 1 or above to obtain output.
- `playbook04-artifact.yml` - A simple playbook that saves a picture from NASA. 
 - `playbook05-fails.yml` - An example playbook that intentionally demonstrates failing tasks to show error handling and retries.
 - `playbook06.yml` - A playbook demonstrating common configuration tasks and idempotence for testing standard Ansible behaviors.
 - `playbook07-gather_facts.yml` - Demonstrates fact gathering and how to consume gathered facts within tasks and conditionals.
 - `playbook08.yml` - Creates a folder on a target host, used to demo SSH.
 - `playbook09_debug.yml` - Demonstrates the `debug` module and uses variables from `vars/playbook09_debug_vars.yml` to illustrate variable handling.


## About
This repository is one of many used in conjunction with Alta3 Research's Ansible Tower / AWX Training program. If you're interesting in Ansible, Tower or AWX training, feel free to contact us [https://alta3.com](https://alta3.com)

## Author
Created and maintained by @RZFeeser
