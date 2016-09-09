# Installation for OpenLDAP

clone repository
```
git clone https://github.com/sios-tech/ansible-openldap-rhel7.git
```

configuration
```
vim ./ansible-openldap-rhel7/roles/ldap/vars/main.yml
```

place of installation
```
vim ./ansible-openldap-rhel7/hosts
```

execute
```
cd ansible-openldap-rhel7
ansible-playbook -u [username] ansible-openldap-rhel7.yml
```
