# GitLab-CICD-monorepo
============
this repo is example of gitlab cicd config for angular monorepo.  
there is four app in monorepo: 
desktop-libs
desktop
shared-libs
mobile

You can view documentation in file ``.gitlab-ci.yml`` but in general: 
6 satges ---> 4 for build 4 repo in conditions of changes in directory 
              1 for ansible copy play-book
              1 for ansible update production server playbook
              
