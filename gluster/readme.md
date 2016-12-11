Gluster with ansible
#########


A simple, rough ansible script I'm working on for my own intents and purposes. Mostly for learning ansible.

What does it do?
- Install GlusterFS-server/client NginX.
- Make a gluster brick and mount it under /var/www/html.


What doesn't it do?
- Requires a host file with the group [gluster_servers] or just edit the .yml's and define your own group.
