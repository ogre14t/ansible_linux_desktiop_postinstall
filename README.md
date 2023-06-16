# ansible_linux_desktiop_postinstall
Post install playbook for Linux setup

sudo dnf install ansible

ssh-keygen -t ed25519 -C "o.watkins@protonmail.com"

upload public key to github

ansible-pull -U https://github.com/ogre14t/ansible_linux_desktop_pontinstall.git 

if errors:

curl -LO https://aka.ms/gcm/linux-install-source.sh &&
sh ./linux-install-source.sh &&
git-credential-manager-core configure

git config --global credential.credentialStore secretservice

pull Obsidian folder

## local install
git clone the repo
`sudo ansible-playbook local.yaml`
