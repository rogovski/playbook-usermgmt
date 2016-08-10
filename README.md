### Create an Admin

```bash
ansible-playbook -i hosts playbook.yml --extra-vars="username=jim password=passjim admin=yes action=create_user"
```

### Create a non Admin

```bash
ansible-playbook -i hosts playbook.yml --extra-vars="username=jim password=passjim admin=no action=create_user"
```

### Delete user

```bash
ansible-playbook -i hosts playbook.yml --extra-vars="username=jim action=delete_user"
```

### Sources

* [playbook intro](http://docs.ansible.com/ansible/playbooks_intro.html)
* [thinkingmonster](https://thinkingmonster.wordpress.com/it-automation/386-2/ansible-roles/)