# playbook-raspberry

1. Flash rasbian image to sd card
2. Enable ssh
```bash
touch /Volumes/boot/ssh
```
3. Install ansible
```bash
sudo pip3 install ansible
```
4. Apply ansible
```bash
 ansible-playbook playbook.yaml -i hosts.ini
 ```


##Application
### Portainer
http://{{ip}}:9000/

### Bitwarden
https://{{ip}}:8082/

### Adguard
http://{{ip}}:9999/

### uptime-kuma
http://{{ip}}:3001/