## Steps to reproduce Arch environment

1. Install Arch on new machine with `ansible git stow` packages installed
2. `git clone https://github.com/michaelzusev/.dotfiles.git`
3. `ansible-playbook -K ~./.dotfiles/ansible-playbooks/playbook-1.yml`
4. Login to google, github, bitwarden
5. Setup Github SSH


## Bazecor
1. Download AppImage and put on Desktop
2. `chmod +x ./Bazecor`
3. `sudo ./Bazecor --no-sandbox`
