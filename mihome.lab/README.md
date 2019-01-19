ansible-playbook -i ../inventories/dev/hosts build_vm.yml --vault-id dev@../vaults/.dev_vault_pass -vvv --extra-vars "guest_vm_state=poweredon"

