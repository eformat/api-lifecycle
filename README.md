# api-lifecylce workshop

- Check inventory for variables.
- Working `oc` login.

Install

```
ansible-playbook -i workshop.inventory install.yml
```
Uninstall
```
ansible-playbook -i workshop.inventory uninstall.yml
```

Provisions:

- RedHat Single Sign On Server
- 3Scale API Management
- Apicurio
- Microcks

![api-lifecycle](images/api-lifecycle-1024x709.png)