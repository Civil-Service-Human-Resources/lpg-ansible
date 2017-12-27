# LPG Ansible Role

`requirements` to run ansible

 * ansible : ` brew install ansible`
 * pem file for ansible to ssh into hosts : ` need lastpass or something similar to share secrets`  
 * ansible vault password : ` need lastpass or something similar to share secrets`

add the pem to the root directory

```
ansible-playbook site.yml -i environments/dev --ask-vault-pass
```