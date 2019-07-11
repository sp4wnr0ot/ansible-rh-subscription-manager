ansible-subscription-manager
=============================

This will configure a Red Hat Enterprise Linux 7 subscription manager, registering
it either to the portal or to a Red Hat Satellite 6.


Requirements
------------
A valid Red Hat subscription.


Role Variables
--------------
rh_username
rh_password
rh_poolid


Dependencies
------------
None


Example Playbook
----------------
    - hosts:
        - rhel7-servers
      roles:
        - goern.rh-subscription-manager


License
-------
GPLv3


Author Information
------------------
Christoph Görn <goern@redhat.com>


References
----------
# ansible-subscription-manager
