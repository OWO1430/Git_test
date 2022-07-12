# Git
## Starting a new project
1. Build a new responsitory
2. Clone it to local
<pre><code>git clone 'website'
</code></pre>
3. Edit and push
<pre><code>git add.
git commit -m "description" 
git push
</code></pre>
## Reversing the version
<pre><code>//display previous version
git log
git log --pretty=oneline // To simplize

//reset
git reset --hard HEAD^ // return to last version
git reset --hard (hash_num)
</code></pre>
## Common used command
<pre><code>git config --list
git status 

git remote -v #查詢 origin url  ，確認目前Git遠端伺服器網址
git remote set-url "別名" "url"  #更換Git遠端伺服器位網址
git remote add "別名" "url"

git branch "分支名稱" #產生分支
git checkout "分支"
git pull = git fetch(查看) + git merge (同步分支)

git push --set-upstream origin "分支"
git commit -am "message" (同時 add 以及commit)
git clone --branch <branchname> <remote-repo-url> 拉取特定分支
</code></pre>

## Other: Set ssh key
<pre><code>$ ssh-keygen  
</code></pre>
Refference: [Link](https://blog.jaycetyle.com/2018/02/github-ssh/)
