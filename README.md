# Proxmox_In_VirtualBox

- network select bridge mode and physical newtork card ( because working web gui ) 
- on nested mod, command promot virutal box directory:

      cd Program Files\Oracle\VirtualBox
      .\VBoxManage.exe list vms 
      .\VBoxManage.exe modifyvm "Proxmox" --nested-hw-virt on
