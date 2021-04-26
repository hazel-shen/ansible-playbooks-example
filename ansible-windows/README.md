# Windows Ansible Examples

## Windows Update Example

ansible-playbook -i <your inventory file> list_vm_installed_updates.yml -e '{"inputs": {"whitelist": [], "blacklist": ["Windows Malicious Software Removal Tool"]}}'
