# centos7-using
centos7 使用记录，个人备忘录

#### 0000-设置中文man

```bash
# 安装中文 man
yum install man-pages-zh-CN.noarch

# 添加 cman 命令别名
echo "alias cman='man -M /usr/share/man/zh_CN'">> /etc/profile

# 使 cman 命令生效
source /etc/profile
```
