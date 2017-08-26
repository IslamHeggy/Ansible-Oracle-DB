# Ansible-Oracle-DB
A script for automating the oracle DB 11.2 express edition installation on SUSE Linux Enterprise 11 sp3.


# How to use
* You should specify the servers' ips or the machines you want to run the script on in the hosts file.
* You should put the url for downloading oracle database from the source or if you already have the source on the remote machine just comment the download oracle module.
* You should also put your oracle database source path in the oracle_dest variable.
* In case you are not using the same distribution, the same version and you don't have the configuration error then you can comment the Copy Modified Configuration Scripts module.
