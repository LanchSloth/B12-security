Artifactory
=========

This role installing artifactory to remote system.

Requirements
------------

**None**

Role Variables
--------------

:one: **jfrog_artifactory_password**  - *password for accessing jfrog artifactory web site* <br>
</br>
:two: **jfrog_artifactory_username**  - *username for accessing jfrog artifactory web site* <br>
</br>
:three: **jfrog_artifactory_lic**     - *license to put for JFrog Artifactory pro*

Dependencies
------------

**postgresql**  - *role with defined vars set*

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role:artifactory , jfrog_artifactory_username: admin, jfrog_artifactory_lic: lic, jfrog_artifactory_password: password }

*ALl other variables please keep in secret*

License
-------

BSD
