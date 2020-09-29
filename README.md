git操作

```javascript
git clone https://github.com/light-hong/ssg-react-admin-class.git //1.创建远程仓库/clone远程仓库
git init // 初始化本地仓库工作区
git add . // 添加至暂存区
git commit -m'注释' // 提交至版本区
git remote add origin https://github.com/light-hong/ssg-react-admin-class.git // 关联至别名为origin的远程仓库
git push origin master // 推送至远程master分支
git checkout -b dev // 创建本地dev分支并切换到dev分支
git push origin dev // 将本地dev分支推送至远程dev分支
git branch //查看所有分支
git checkout -b dev origin/dev // 根据远程dev分支创建本地dev分支
```

