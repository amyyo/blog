# 远程服务器GIT 协作
## 克隆仓库
```bash
git clone ssh://example.com/~/www/project.git     //先从服务器克隆一个库并上传
```
## 推送修改
```bash
$ git push   //修改之后可以进行推送到服务器
$ git push -u origin master  //推送至主分支
```
## Git 工程迁移
```bash
$ git remote add-url origin https://xxxx.git # 增加资源库地址
$ git remote set-url origin git://new.url.here # 关联资源库新地址
```
## 取回更新
```bash
git pull
```
```bash
git add  // 暂存
git commit -am "注释" // 暂存加注释
git commit -m "注释"
```
