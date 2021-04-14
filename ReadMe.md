## 1、git reset有三个模式：
### （1）git reset --soft HEAD^
  `不删除工作空间改动代码，撤销commit，不撤销git add .`
### （2）git reset --mixed HEAD^
  `不删除工作空间改动代码，撤销commit，并且撤销git add . 这个为默认参数,git reset --mixed HEAD^ 和 git reset HEAD^ 效果是一样的`
### （3）git reset --hard HEAD^
  `删除工作空间改动代码，撤销commit，撤销git add，此操作后恢复到上一次的commit状态 .`

## 2、修改commit massage
`（1）方法一：先git reset --soft HEAD^，再commit`
`（2）方法二：git commit --amend，进入vim，'i’进入insert模式，输入文字,'esc’回到命令模式，‘:’进入底层模式，wq保存并且退出。`

ok
