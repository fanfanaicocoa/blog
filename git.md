#Git学习
##git clone 
>git clone git@github.com:fanfanaicocoa/blog.git
`拉取git仓库`

##git fetch
>1:git fetch 拿到全部远程分之放到.git/FETCH_HEAD里
>2:git merge 动作默认是当前分支

##git pull
>git pull = git fetch+merge
>拉取得代码

##git checkout
>git branch xx 新建xxx分支
>git checkout xxx 切换到xxx分支
>git checkout -b xxx 新建xxx分支并切换到xxx分支

##git merge
>首先切换到A分支
>git merge b
>B分支上的内容就合并到A上了

##reset revert
>reset 回滚
>>比如有a,b,c三个提交 reset b那么b以后的提交都没了
>
>revert b 会在c后添加一个revert b的commit 
>>就会是a,b,c,revert b

##cherry pick
>不想合并所有对方提交,只想合并某一个
>>B分支上git log :a,b,c
>>A分支只想合并B分支的b Commit
>>A cherry-pick B


