# node

TODO: Enter the cookbook description here.

Step by Step guide to building AMIs:
Install packer
https://www.packer.io/intro/getting-started/install.html
Need the app repo and Berkshelf
Berkshelf is a dependency manager for Chef cookbooks. Basically like your metadata file.
Need working repo for MongoDB and Nodejs locally
Ensure the Github repo works and passes all tests and add to Berksfile with this syntax for instance:
cookbook 'node', git: 'git@github.com:j2020v/chef-node-cookbook.git'
Created .json packer file
Template for .json file can be found in this link https://www.packer.io/intro/getting-started/build-image.html
Echo keys in .bash_profile (ACCESS KEY AND SECRET)
Describe variables and what infrastructure it is meant to use
Export variables
Built AMIs externally and carried out provisions after
