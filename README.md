Limesurvey
=========

Installs the Open Source on-line survey application Limesurvey on http://host:8080/limesurvey .

Requirements
------------

Package names are based on the Debian distribution.

Role Variables
--------------

The variable **limesurvey_with_services** controls the installation of Apache and MySQL and defaults to *true*.

Default **admin** password is **password** (sha256). 

Dependencies
------------

None.

Example Playbook
----------------

```
- name: Limesurvey
  hosts: all
  sudo: yes

  roles:
    - limesurvey
```

License
-------

BSD

Author Information
------------------

Thomas.Berton@UGent.be