# Ansible ####

This is ansible repository
```
sudo ansible-pull -U https://github.com/pdamaszk/ansible.git
```
```
sudo journalctl | grep CRON | grep ansible-pull
```
```
sudo crontab -u velociraptor -l
```
```
ansible all --key-file ~/.ssh/ansible_ed25519 -i hosts -m ping
```
```
job: ansible-pull -o -U https://github.com/pdamaszk/ansible.git >> /home/velociraptor/logfile.log 2>&1
```


# Some chenges here 2nd time ##
# Some 3rd chenge with it
# 4th line chenged
