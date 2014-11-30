rails_ansible
=============

Ansible script to deploy rails


install rvm and memcached from the galaxy on your local machine

```
ansible-galaxy install rvm_io.rvm1-ruby
ansible-galaxy install bennojoy.memcached
```
create a deploy keyfile 
```
ssh-keygen -t rsa -C "deployer@bladiebla.org"
```
add the PUBLIC keyfile to guthub
move the private keyfile to `roles/rails/files/deploy_rsa`

