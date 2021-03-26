1.git右键bash here

2.设置用户

~~~
git config --global user.email xxxxxxx@qq.com     #邮箱信息
git config --global user.name  xxxx               #git用户名
~~~

3.查看用户信息

~~~
git config -l
~~~

4.上传

~~~
git add .   #把所有文件加到暂存区
git commit -m 'modify'  #不能为空，提交暂存区的内容
git push   #上传文件
git pull   #同步服务器代码到本地
~~~
