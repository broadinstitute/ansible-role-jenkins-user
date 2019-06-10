# ansible-role-jenkins-user
Ansible role - create jenkins user.  

Basic role that just adds a single user.  This role currently also adds the
jenkins user to the google-sudoers group so that the user can sudo without
a password on GCE instances.

FUTURE: Generalize this into a role that adds users based on some map.
