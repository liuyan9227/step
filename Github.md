# Github

## 全局配置

```java
git config --global username liuyan9227
git config --global useremail liuyan9227@163.com
```

## 创建本地仓库

1. 创建本地仓库 git-workspace
2. 并在cmder中执行 git init 初始化本地仓库

## SSH地址

获取github项目的ssh地址

## SSH key

```java
ssh-keygen -t rsa -C "liuyan9227@163.com"
```

## id_rsa.pub

复制公钥: C:/用户/Max/.ssh/id_rsa.pub

## Github设置公钥

Setting --> SSH and GPG keys 中设置公钥

## 添加远程仓库

```java
git remote add origin SHH地址
git remote [-v]"查看"[地址]
```

## 下载 (浏览者)

```java
git clone HTTP地址
```

## 同步代码

增量更新, 下载远程仓库的所有版本代码

```java
git pull origin master
```

## 添加 (协作者)

项目中 --> Settings --> Collaborators --> 用户名or邮箱

