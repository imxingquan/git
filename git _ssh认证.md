## git SSH 认证

根据账户创建ssh key
```
$ ssh-keygen -t rsa -b 4096 -C "402059985@qq.com"
```

复制~/.ssh/id_rsa.pub的内容，在github.com的自己的settings中新建SSH Keys 然后粘贴保存

## 参考

https://help.github.com/categories/authenticating-to-github/