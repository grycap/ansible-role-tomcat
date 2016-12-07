[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/grycap/ansible-role-tomcat.svg?branch=master)](https://travis-ci.org/grycap/ansible-role-tomcat)

Apache Tomcat Role
=======================

This ansible role installs [Apache Tomcat ](https://tomcat.apache.org/).  

>_Warning_  
(If needed) the java version installed in Ubuntu 14.04 is 1.7.   Centos 6 , Centos 7 and Ubuntu 16.04 will install java 1.8 .  
Also tomcat version is not fixed, this role will always install the latest version of the tomcat package available at the repositories.

Example Playbook
----------------

This an example of how to install this role:

    - hosts: server
      roles:
      - { role: 'grycap.tomcat' }

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled.  
If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks
