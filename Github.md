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

## 常用命令

```java
git status		-- 查看状态
git add . 		-- 添加至缓存区
git commit -m "日志"		-- 提交至本地仓库
git rm 文件名			-- 删除文件
git rm --cached 文件		-- 不管理此项目
git mv old new		-- 重命名
git log			-- 查看日志
git reset --hard 7位版本号		-- 回退版本
git reset head 文件		-- 暂存退回已修改
git checkout --文件		-- 已修改退回未修改
git push origin master		-- 提交远程仓库
git pull origin master		-- 下载远程仓库
git remote rm origin		-- 解除远程仓库
```

