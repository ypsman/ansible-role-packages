Ansible Packages
=============
Role to easy install and remove Packages.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.packages
          packages:
            - vim
            - htop
          packages_remove:
            - exim4
