# vsftp_manage
用于管理vsftpd，包含安装、卸载、添加虚拟用户等，详细请执行./vsftpd_manage查看

Usage: ./vsftp_manage [cmd] [options]  
cmd:  
install																	install vsftpd by yum  
uninstall																uninstall vsftpd by yum  
add_user																add ftp virtual user  
del_user																delete ftp virtual user  
start																		start vsftpd  
stop																		stop vsftpd  
restart																	restart vsftpd  
reload																	reload vsftpd  
status																	check vsftpd status  
set_onboot															set vsftpd onboot  
unset_onboot														unset vsftpd onboot  
options:  
username password												when cmd is add_user, it must input username and password  
username																when cmd is del_user, it must input username  
eg: add_user test 123456  
Notes:  
The default port is 60521
