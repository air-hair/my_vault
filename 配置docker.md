---
type: Note
---
# 配置docker

sudo rpm -ivh --nodeps [containerd.io](http://containerd.io)-1.6.28-3.1.el8.x86_64.rpm\
sudo rpm -ivh --nodeps docker-ce-cli-20.10.24-3.el8.x86_64.rpm\
sudo rpm -ivh --nodeps docker-ce-20.10.24-3.el8.x86_64.rpm\
*# 将下载的文件复制到系统路径*\
sudo cp /path/to/docker-compose-linux-x86_64 /usr/local/bin/docker-compose\
\
*# 添加执行权限*\
sudo chmod +x /usr/local/bin/docker-compose\
\
*# 验证版本*\
docker-compose --version
