1,  ssh-keygen 生成公私钥

ssh-keygen -t rsa -b 4096 -C "XXX@126.com"

2, 生成成功后，把  id_rsa.pub 拷贝到 github  新建的 SSH keys 中

cat ~/.ssh/id_rsa.pub 

将内容在GITHUB中更新ssh-token设置。

3,    生成TOKEN 

Settings / Developer settings/Personal access tokens (classic)

生成新的TOKEN



4, 

git remote add  origin https://github.com/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/youtube-dl-GUI.git
# 提交代码
git push -u origin master
