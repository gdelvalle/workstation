## workstation cookbook
This cookbook should ease my transition between work stattions and help me to centralize my content ( other stuff will go in private repos) in case of failure.
The goal is to make is partially OS agnostic ( really only needs to work on Max OS X and  RHEL family and debian family as those are the distributions I use)

#### Apps:
- chefdk
- rvm
- vagrant
- virtualbox
- Docker Toolbox (deprecates boot2docker)
- python 2.7 + setup tools/pip
- faws-cli

#### gems(in chefdk):
- knife-rackspace ( knife plugin)
- knife-docker (knife plugin)
- knife-solo_data_bag
- knife-solo

#### system python modules
- virtualenv
- virtualenvwrapper
- 
##### Virtualenvs:
- supernova
- rackspace nova extensions
- aws cli
- rax montioring cli
- 



Configs to bring along:
- ssh config
- bash dot files ( including chef helper functions and ssh discovery script)
