# github_ubuntu_readme
The usage of github on ubuntu platform

method1:
1. create an reposition on github, such as convert-format
2. use ssh url to git clone the github reposition:
    git clone git@github.com:ptkang/convert-format.git
3. cd convert-format/
4. copy the local code to cloned code dir, such as convert-format
5. add local code, commit, and push
    git add -A
    git commit -m "first version of convert format"
    git push -u origin master

method2:
0. create an reposition on github, such as h265bs
1. mkdir h265bs
2. cd h265bs
3. git init
4. git remote add origin git@github.com:ptkang/h265bs.git
5. git pull origin master
6. git branch
7. copy the local code to cloned code dir, such as convert-format
8. add local code, commit, and push
    git add -A
    git commit -m "first version of h265 parse bs to stream or file"
    git push -u origin master # 第一次提交分支 'master' 设置为跟踪来自 'origin' 的远程分支 'master', 不然之后git pull会报不知道分支错误
    git push origin master # 之后提交

set upstream method:
git clone git@github.com:<username>/cpython.git
cd cpython
git remote add upstream git@github.com:python/cpython.git
git remote -v
    origin  git@github.com:<your-username>/cpython.git (fetch)
    origin  git@github.com:<your-username>/cpython.git (push)
    upstream        git@github.com:python/cpython.git (fetch)
    upstream        git@github.com:python/cpython.git (push)
