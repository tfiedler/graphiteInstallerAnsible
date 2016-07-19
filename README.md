# graphiteInstallerAnsible
Ansible role to install graphite with gunicorn, nginx, and supervisor.

Mainly this is a project to demonstrate all things Ansible, additionally because graphite is cool and useful. I have been installing and using on Ubuntu 14.04 LTS because installing on RHEL / CentOS is a major PITA.

Main install:
  ansible-playbook -i scripts/ec2.py graphite.yml --tags graphite_main
Main config:
  not yet completed

=== CHANGE LOG === 

July 18, 2016
* main graphite plus prereqs and meta all install cleanly on ubuntu 14.04 LTS 

July 19, 2016
* Supervisor installs cleanly
* Supervisor /etc dirs created
* init default supervisor config created

July 20, 2016
* Fixed a bunch of typos
* ec2 role is working
* started working on supervisor config
