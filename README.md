MatteoNardi.quick-python-deploy
===============================

Quickly deploy a Python application:
- Rsync
- virtualenv



This lame but simple deploy strategy was optimized for Raspberry PI.

Role Variables
--------------

```
app_name: # name of application to deploy
dest_folder: '/opt/{{app_name}}/' # location where app will be located
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

