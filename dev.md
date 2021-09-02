1. git 删除 .vscode .idea 等已提交文件夹
```git
git rm -r --cached .idea/
git commit -m 'remove .idea'
git push 
```