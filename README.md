hosts-deploy
=========
Deploy inventory hosts to ``/etc/hosts``.

Requirements
------------

None.

Role Variables
--------------

```python
# defaults/main.yml
# the group name, which you want to deploy the hosts 
# included by the group.
GROUP_NAME: all
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ihaolin.hosts-deploy, GROUP_NAME: 'webservers' }

License
-------

MIT

Author Information
------------------

