# brook-relay-doubi
逗比的 brook-pf 转发脚本备份

- 去除了添加防火墙规则（不喜欢被乱改系统）
- wget 进行证书验证
- 禁止更新
- 只下载指定版本 v20200201
- 所有文件均在该repo里面

解决证书问题
```
# Debian
apt-get install ca-certificates -y
# CentOS
yum install ca-certificates -y
```

下载
```
wget https://raw.githubusercontent.com/ss-daily-backup/brook-relay-doubi/master/brook-pf.sh && chmod +x brook-pf.sh
bash brook-pf.sh
```
