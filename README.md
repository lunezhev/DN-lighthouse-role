Role Name
=========

lighthouse-role

Requirements
------------

None

Role Variables
--------------

- nginx_username - имя пользователя, из-под которого будет запущен процесс nginx
- lighthouse_vcs - путь до репозитория lighthouse
- lighthouse_vcs_version - версия внутри репозитория lighthouse (хэш коммита)
- lighthouse_location - путь до директории с lighthouse
- lighthouse_access_log_name - имя лог-файла nginx для web-сервиса lighthouse

Dependencies
------------

None

Example Playbook
----------------

```text
---
- name: lighthouse
  hosts: lighthouse
  roles:
    - lighthouse
```

License
-------

BSD

Author Information
------------------
 None
