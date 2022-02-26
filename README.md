# playbook-raspberry

1) Flash rasbian image to sd card
2) Enable ssh
touch /Volumes/boot/ssh
3) Install ansible
sudo pip3 install ansible
4) Apply ansible
 ansible-playbook playbook.yaml -i hosts.ini