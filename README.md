Bare-bones Ansible script to deploy a Drupal site to a set of servers.

Assumes:
1) The user running this script has ssh access to all servers -- if a different username is used remotely, edit ~/.ssh/config as needed.
2) The deploy user on the servers has ssh key and ssh config required for accessing the git repo.

To Use:
* Add servers to prod-web, stage-web, dev-web inventory groups.
* Update `group_vars/all` to point to your git repo
