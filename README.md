This role contains Ansible playbooks used for configuring an
Ansible Tower instance.

Note: As an alternative to supplying the Tower credentials for
each module, you can create a configuration file located at
"~/.tower_cli.cfg" with the following format and contents:

host = tower.example.com
username = admin
password = adminpassword


tower-ldap:
---------------
Configure LDAP/Active Directory authentication parameters.
