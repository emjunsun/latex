###设置latex支持中文

1.在ubuntu终端输入以下命令，以查看系统是否已安装了中文字体。
`
fc-list :lang=zh-cn | grep CN
`
如果没有输出，即系统没有安装中文字体，那么需要进行安装：
`
sudo apt-get install ttf-arphic-uming
`
---