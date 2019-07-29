# Ubuntu

**Ubuntu 命令** 

 1. 持续更新...

 2. 从目录查询文件 find ：
     	sudo find / -name "mongo*"  	按文件名*号表示通配符
　	find　/ -size 2M   　　　	按文件大小
　　	find   -perm 777						按文件权限
 3. 查询进程:   ps -aux|grep mongo
 4. 查看进程端口: ps -ef|grep mongod    #查看mongo端口
 5. 杀死进程:  kill -9 {pid}
 6. 新建文件:　　touch {filename}
 7. 自动补全路径:  tab键
 8. gedit 编辑文件
 9. 按关键字查询文件内容:    
    vi  filename   
　/{keyword}  回车后按　N翻下一页　n上一页

 10. sudo lsof -i:8005 | gref LISTEN   监听端口
 11. tail -f catalina.out 追踪文件尾部内容更新
 12. sudo cp -f {filepath} {destinct path}
 13. sudo ssh -i {access-file-path} {username}@{ip} -p {port}
 14. chmod 777
 15. sudo rm -f  删除文件 
sudo rm -rf  删除文件夹  sudo rm -rf /home/ianguo/.local/share/Trash/files/
 16. sudo crontab -e 编辑crontab内容
 17.  卸载软件: sudo apt-get purge [softwareName]  
 18. sudo nautilus
 19. sudo vi /etc/profile   source /etc/profile
 20. 



 
