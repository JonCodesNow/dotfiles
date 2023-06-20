# Mac Dotfiles
This repository provides an automated function of installing necessary packages to a MacOS using Ansible.

## Necessary Packages
Before running this bootstrap you will need to make sure you have Ansible installed on your device. Run the command below
```

python3 -m pip install --user ansible
```

## Usage

After installing Ansible, run the bootstrap command 
```

ansible-playbook bootstrap.yaml
```
This will install the packages that are currently in use on my Mac. 
