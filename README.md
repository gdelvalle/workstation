## workstation cookbook
This cookbook should ease my transition between work stations and help me to centralize my content ( other stuff will go in private repos) in case of failure.
The goal is to make is partially OS agnostic ( really only needs to work on Max OS X and  RHEL family and debian family as those are the distributions I use)

#### Apps:
- chefdk
- rvm
- vagrant
- packer
- virtualbox
- Docker Toolbox (deprecates boot2docker)
- python 2.7 + setup tools/pip
- faws-cli 
- editorconfig
- sublime text

#### sublime plugins
- cloudformation
- editorconfig

#### vim plugins
- pathogen
- vim-json 
- vim-yaml

#### gems(in chefdk):
- knife-rackspace ( knife plugin)
- knife-docker (knife plugin)
- knife-solo_data_bag
- knife-solo

#### system python modules
- virtualenv
- virtualenvwrapper


##### Virtualenvs:
- supernova
- rackspace nova extensions
- aws cli
- rax montioring cli
- heat



Configs to bring along:
- ssh config ( ~/.ssh/config)
- ~/.ssh/ssh_config ( defines some fucntions that discovers network  to set proxy)
- dot files (link to repo here) ( e.g. ~/.editorconfig)

