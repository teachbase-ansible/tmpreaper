tmpreaper
========

Install and configure tmpreaper.

Installation
--------------

`ansible-galaxy install palkan.tmpreaper`

Role Variables
--------------

`defaults/main.yml`

| Name                        | Default Value |  Description    |
|-----------------------------|---------------|-----------------|
| tmpreaper_time              | '7d' | |
| tmpreaper_dirs              | '/tmp/.' | |
| tmpreaper_delay             | '256' | |
| tmpreaper_protect           | '' | |
| tmpreaper_options           | '' | |

Example Playbook
-------------------------
```yml
  - hosts: servers
    roles:
       - palkan.tmpreaper
```
