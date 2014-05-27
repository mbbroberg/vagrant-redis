#Playing with Redis & Vagrant

I'm hacking together a few ways by which you can spin up Redis into local test environments.


##with-ansible

Code "forked" from [this repo](https://github.com/Mayeu/ansible-playbook-redis.git).


##with-chef

Code brought down from [Chef's community](community.opscode.com/cookbooks/redisio) and the `Vagrantfile` was modified from past code.

###How to use it

Either directory has its own `Vagrantfile` from which you can boot a VM that will include Redis. Nothing beyond that is guaranteed. Feel free to fork and add!
