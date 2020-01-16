Git is a distributed version control system.</br>
Git is free sofware distributed under the GPL.</br>

将当前文件夹初始化为本地仓库</br>
git init

将文件(文件夹)新增至本地仓库</br>
git add example.txt     //git add example/</br>
提交本次变更</br>
git commit -m "备注"</br>
推送至远程仓库</br>
git push</br>

删除文件</br>
git rm example.txt</br>
git commit -m "删除"</br>
恢复被删除的文件</br>
git checkout example.txt</br>

添加远程仓库</br>
git remote add [name] [url]</br>
eg:</br>
git remote add origin git@github.com:computeristrue/myRepository.git

从远程仓库拉取到本地好像需要创建本地分支</br>
git checkout -b 本地分支X origin/远程分支X  -b会创建并切换到本地分支</br>
查看当前分支</br>
git branch        -r 查看远程分支</br>
切换分支     此时本地仓库内文件会相应发生变化</br>
git checkout master</br>

git merge dev    把dev分支的文件合并到当前分支</br>

git branch -d dev 删除dev分支，需要dev分支的文件全部提交或者推送至远程之后才行</br>
