Ansible Role: Nginx
=========

Эта роль установит Nginx на ОС CentOS.

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены вместе со значениями по умолчанию (см. `defaults/main.yml`).

Dependencies
------------

Также необходимо открыть следующие порты в firewall
- port: 80/tcp
или
- service: http

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - nginx

License
-------

BSD

Author Information
------------------

Chubik Sergey.
