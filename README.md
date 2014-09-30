ansible-playbooks
=================

Some ansible playbooks for servers


Environment
-----------

The environment used for this playbooks is the following:

 * Debian GNU/Linux
 * The `ansible` software, version >= 1.7.1
 * An *ansible* user with sudo capabilities in all the remote hosts
 * Passwordless SSH and sudo between the ansible server and remote hosts using SSH public key.
 * A **/etc/ansible/hosts** file with a 'mylist' group of remote hosts

How to run
----------

For example:

	% ansible-playbook playbooks/debian-security-update.yml
