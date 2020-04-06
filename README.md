OS UPGRADE
=========

This main goal of this role is to upgrade  your Redhat based system



Role Variables
--------------

check_disk_device_path 
check_disk_limit_value 

reboot_default 
server_update_reboot_pre_reboot_delay
server_update_reboot_post_reboot_delay
server_update_reboot_reboot_timeout

server_update_yum_exclude_pkgs
server_update_yum_install_pkgs



Example Playbook
----------------


    - hosts: all
      roles:
         - { role: os_upgrade_dev }



Author Information
------------------

Wilfried Bessovi 24/03/2020
