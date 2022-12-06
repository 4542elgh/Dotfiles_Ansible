```bash
pacman -S python
pacman -S python-pip

curl -LO https://github.com/4542elgh/Dotfiles_Ansible/archive/refs/heads/main.zip
sudo pacman -S unzip
unzip main.zip
cd Dotfiles_Ansible-main

ansible-playbook -i hosts playbook.yaml --ask-vault-pass -v
```
