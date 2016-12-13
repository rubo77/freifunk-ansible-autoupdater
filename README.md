# Router sysupgrade script

### Vorraussetzungen:

    apt-get install ansible sshpass


### ausführen

    ANSIBLE_SCP_IF_SSH=y ansible-playbook autoupdate.yml -v

### debuggen

    ANSIBLE_SCP_IF_SSH=y ansible-playbook autoupdate.yml -vvvv

### TODO

- sysupgrade funktioniert so noch nicht
