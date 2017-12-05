Create an hosts file starting from hosts.template,
be sure that in /etc/motd of the hosts there is a description like:
 
=======
description
=======

then run:

ansible-playbook -i hosts  -u root -k playbooks/checkso.yml
