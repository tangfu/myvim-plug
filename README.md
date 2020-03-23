# myvim-plug

代码即文档

1. plug依赖于vim8
# 卸载老的vim
yum remove vim* -y

# 下载第三方yum源
wget -P /etc/yum.repos.d/  https://copr.fedorainfracloud.org/coprs/lbiaggi/vim80-ligatures/repo/epel-7/lbiaggi-vim80-ligatures-epel-7.repo

# install vim
yum install vim-enhanced sudo -y
根据需要添加alias vi=vim

2. 安装插件
:PlugInstall
