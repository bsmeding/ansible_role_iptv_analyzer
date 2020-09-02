# ansible_role_iptv_analyzer
Ansible role to install IPTV multicast analyzer   WARNING! CURRENLY IN DEV STATE DO NOT USE

Original version from Jesper Dangaard Brouer - https://github.com/netoptimizer/IPTV-Analyzer stripped down, updated and written as Ansible role.

MySQL / MariaDB inspired by: https://github.com/bertvv/ansible-role-mariadb

# Ansible host requirements
* Ansible >2.8
* python module netaddr

#Prerequistics
We use Grafana as frontend instead of perl version because better graphs and alert possibilities. The installation of Grafana is out of scope of this role. I recommend of using the Ansible role cloudalchemy.grafana to install Grafana (ansible-galaxy install cloudalchemy.grafana)
