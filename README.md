# CentOS7-and-Mysql-Install
centos7, MySQL, Virtual Box, Vagrant, MysqlWorkbench, Apache server Install and run.

1.Insatlling centos7 and vagrant with oracle virtual box:
--------------------------------------------------------------

1. Download and install Oracle Virtual box
2. Download and inastall Vagrant
3. create Folder: vagrant/centos7/
4. Open gitbash in that folder
```
$ vagrant init
```
6. Open VagrantFile and edit config.vm.box = "centos/7" this.
```
$ vagrant up
$ vagrant ssh
```
Done !

</br> </br>
<a href="https://imgur.com/MSlCAOm"><img src="https://i.imgur.com/MSlCAOm.png" title="source: imgur.com" /></a>

2.Installing Mysql:
---------------------
Do--> MySqlInstall in CentOS.txt

3.Connect Mysql Workbench with vagrant centos7
-----------------------------------------------
Do--> Mysql_Connection_with_Vagrent_CentOS7.txt

4.Installing Apache in centos7:
----------------------------------
Do--> apache install centos7.txt
