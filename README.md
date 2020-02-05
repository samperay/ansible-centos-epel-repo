# ansible-centos-epel-repo

Role Name
=========

EPEL Repository for CentOS

Requirements
------------

Role runs for CentOS and RedHat

Role Variables
--------------

Available variables are listed below, along with default values

```
epel_repo_url_latest: "https://dl.fedoraproject.org/pub/epel/epel-release-latest-{{ ansible_distribution_major_version }}.noarch.rpm"
epel_repo_key: "/etc/pki/rpm-gpg/RPM-GPG-KEY-EPEL-{{ ansible_distribution_major_version }}"
epel_file_path: /etc/yum.repos.d/epel.repo
```

Dependencies
------------


Example Playbook
----------------

```

 - hosts: servers
   roles:
    - samperay.ansible-centos-epel-repo
         
```
License
-------

BSD

Author Information
------------------
Created on 05/Feb/2019 Wednesday 14:32 IST by sunlnx@gmail.com
