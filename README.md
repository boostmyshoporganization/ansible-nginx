Ansible Nginx
==============

Install and configure nginx on Debian server.

Installation
------------

git submodule add git@github.com/boostmyshoporganization/ansible-nginx roles/nginx

```yaml
roles:
    - nginx
```

Configuration
-------------

```yaml
nginx:
  variables:
    - { name: client_max_body_size, value:  5M }
```