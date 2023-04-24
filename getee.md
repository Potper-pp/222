ssh-keygen -t rsa -C "potper.pp@hotmail.com"




ssh-keygen -t ed25519 -C "potper.pp@hotmail.com"  

https://gitee.com/potper/giteetest

Git 全局设置:
```
git config --global user.name "POTPER"
git config --global user.email "potper.pp@hotmail.com"
```
创建 git 仓库:
```
mkdir giteetest
cd giteetest
git init 
touch README.md
git add README.md
git commit -m "first commit"
git push -u origin "master"
```

已有仓库?

```
cd existing_git_repo
git remote add origin git@gitee.com:potper/giteetest.git
git push -u origin "master"
```