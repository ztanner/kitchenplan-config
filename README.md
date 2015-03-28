# Kitchenplan Configuration

This is a Kitchenplan configuration repository. This repository contains all configuration to install and configure our OSX workstations. More information about Kitchenplan and on how to use it can be found in the [Kitchenplan README](https://github.com/kitchenplan/kitchenplan).

1) Fork this repo https://github.com/damonpetta/kitchenplan-config
2) Copy damon.yml to your username.yml and edit the settings (sudo users, computer name, git)
3) commit changed to your forked repo
4) open terminal 
	$ gem install kitchenplan
	$ kitchenplan setup # when asked "Do you have a config repository? [y,n] “ answer yes and use your forked repo
	$ kitchenplan provision
5) wait for a few hours :)
6) In another terminal setup your github user with your local ssh key and check out the main bottlenose repo.

The kitchen plan setup will install all the requirements; check out the bottlenose repo and then when everything is done we’ll work on getting the app setup.
