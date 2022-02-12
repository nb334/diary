<div hidden="hidden">

# <iframe id="onlineMusic" border="0" frameborder="no" framespacing="0" scrolling="no" allowfullscreen="true" width="220" height="120"> </iframe>

</div>

# 日记
!> 努力的记忆着自己的一切 
> 使用python进行`docsify`的简易部署  
```bash
# 在python2下开启简易的http服务器
nohup python -m SimpleHTTPServer 3000 &
# 在python3下开启简易的http服务器
nohup python3 -m http.server 3000 &
# 杀死开启的http服务器
netstat -ntulp |grep 3000
kill -9 进程号
```