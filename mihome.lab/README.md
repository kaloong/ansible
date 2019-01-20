To build ISO and VMs:
ansible-playbook -i inventories/build/hosts playbooks/build_vm.yml --vault-id dev@vaults/.dev_vault_pass -vvv --extra-vars "guest_vm_state=poweredon"

To shutdown ESXi lab:
ansible-playbook -i inventories/build/hosts playbooks/esxi_adm.yml --vault-id dev@vaults/.dev_vault_pass -vvv -e "host_force=yes host_state=shutdown-host"
