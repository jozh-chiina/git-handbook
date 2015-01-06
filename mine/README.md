Git命令及个人解析
=================

### key 本地库与远程库互联

	# 命令
	ssh-keygen -t rsa
	三次回车，默认目录，默认配置

	# 讲解
	1.进入本地用户下'.ssh'目录，拷贝id_rsa.pub内容；
	2.进入github账户中，右上选项Account settings->SSH keys->Add SSH key，粘贴内容，并保存。

### 创建代码仓库
