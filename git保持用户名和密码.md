### git 保存账户和密码

## 使用缓存保存
```
git config --global credential.helper 'cache --timeout=60000'
```

## 通过文件方式

~/目录创建 .git-credentials 文件 按如下格式输入内容： 

  https://{username}:{password}@github.com 

使用命令激活

```
git config --global credential.helper store
```

~/.gitconfig文件，增加项

[credential]
helper = store
4.OK
