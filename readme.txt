此脚本用于在linux环境上自动化创建domain  

需要修改里面对应的参数

ServerStartMode ： domain启动模式  （开发环境为dev）
ListenPort ： 监听端口
write domain to 在linux的什么目录创建

使用 wlserver_10.3/common/bin/config.sh -mode=silent -silent_script=create_domain.rsp -logfile=create_domain.log 命令执行
