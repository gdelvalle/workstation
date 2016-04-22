## workstation cookbook
This cookbook should ease my transition between work stations and help me to centralize my content ( other stuff will go in private repos) in case of failure.
The goal is to make is partially OS agnostic ( really only needs to work on Max OS X and  RHEL family and debian family as those are the distributions I use)

#### Apps:
- chefdk
- rbenv*
- vagrant
- packer
- virtualbox
- Docker Toolbox (deprecates boot2docker)
- python 2.7 + setup tools/pip
- faws-cli 
- editorconfig
- sublime text
- brew
  - jq*
  - tmux*
  - mtr*
  - dos2unix*

#### sublime plugins
- cloudformation
- editorconfig

#### vim plugins
- pathogen
- vim-json 
- vim-yaml
- vim-ruby

#### gems(in chefdk):
- knife-rackspace ( knife plugin)
- knife-docker (knife plugin)
- knife-solo_data_bag
- knife-solo
- tmuxinator
- guard
- guard-shell
- wirble
- pry
- powder (managing pow)

#### system python modules
- virtualenv
- virtualenvwrapper


##### Virtualenvs/pip modules:
- supernova
- rackspace nova extensions
- aws cli
- rax montioring cli
- heat




Configs to bring along:
- ssh config ( ~/.ssh/config)
- ~/.ssh/ssh_config ( defines some fucntions that discovers network  to set proxy)
- dot files (link to repo here) ( e.g. ~/.editorconfig, ~/.gemrc, ~/.irb, ~/.heatrc, ~/.tmux.conf, ~/.vimrc, ~/.vim)

