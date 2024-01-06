## Steps to reproduce Arch environment

1. Install Arch on new machine with `ansible git stow` packages installed
2. `git clone https://github.com/michaelzusev/.dotfiles.git`
3. `ansible-playbook -K ~./.dotfiles/ansible-playbooks/playbook-1.yml`
4. Login to google, github, bitwarden
5. Setup Github SSH

## Fstab
`sudo vim /etc/fstab`
```
# /dev/sda
UUID=dc2140d1-5808-4d11-ae42-01130aacfe26	/home/michael/vg_data_1 ext4 	defaults	0 0 

# /dev/sdb
UUID=03db44f5-ffeb-4657-a8dc-2760c1bdd5e7	/home/michael/vg_data_2 ext4 	defaults 	0 0
```
`sudo mount -a`


## Bazecor
1. Download AppImage and put on Desktop
2. `chmod +x ./Bazecor`
3. `sudo ./Bazecor --no-sandbox`

