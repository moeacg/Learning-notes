# Windows 系统安装 git 后相关必要配置

## 全局配置
配置 name
```bash
git config --global user.name
```

配置 email
```bash
git config --global user.email
```

配置记住用户名和密码
```bash
git config --global credential.helper wincred
```

## 局部配置
配置 name
```bash
git config user.name
```

配置 email
```bash
git config user.email
```

配置记住用户名和密码
```bash
git config credential.helper wincred
```



## 查看使用的配置信息

查看当前项目使用配置信息

```bash
git config -l
```

查看全局默认使用的配置信息

```bash
git config --global -l
```