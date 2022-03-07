# Ubuntu Desktop Setup
Set up and configure Ubuntu for development and personal use. The playbook and script has been tested on Ubuntu Focal (20.04).

## Install Dependencies
To run ansible playbook, we have to first install python3 and ansible:
```bash
chmod +x install.sh
./install.sh
```

## Run the Playbook
Now we are ready to set up and configure the Ubuntu desktop system based on personal needs:
```bash
ansible-playbook ubuntu_setup.yaml --ask-become-pass -vvv
```
