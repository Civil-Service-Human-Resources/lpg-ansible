# LPG Ansible Role

`requirements` to run ansible

 * ansible : ` brew install ansible`
 * pem file for ansible to ssh into hosts : ` we need a lastpass or something similar to share these type of things`  
 * ansible vault password : ` we need a lastpass or something similar to share these type of things`

add the pem to the root directory

```
ansible-playbook site.yml -i environments/dev --ask-vault-pass
```