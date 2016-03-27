![Git Logo](https://github.com/mzying2013/GitShare/blob/master/logo@2x.png?raw=true)


>Git是一款`免费`、`开源的`、`分布式版本`控制系统，用于敏捷高效地处理任何或小或大的项目。最初由`林纳斯·托瓦兹（Linus Torvalds）`创作。



##Git vs SVN
- 分布式版本 `无需网络，完全独立`


- 分支 `Git的分支实际上仅是一个哈希值文件`


- 元数据存储 `SVN每个目录下都会有.SVN文件，Git只会在目录起点拥有一个.git目录`


- 内容完整性 `版本号是一个哈希值，哈希值是根据文件内容计算出来，所以在发生磁盘故障和网络问题的时候，可以根据版本号来确定文件内容完整性`


- 压缩传输 `Git压缩传输，SVN是一个一个文件传输`


- *无悲观锁 `无法锁定文件（缺点）`*


![SVN vs Git](https://github.com/mzying2013/GitShare/blob/master/svn-vs-git.png?raw=true)



##服务端&Demo
>GitBlit [`http://192.168.1.215:8088/`](http://192.168.1.215:8088/)

- 库 `创建远程库`
- 协议 `git://` `http(s)://` **`ssh://`**
- 用户 `用户``组` `权限` `SSH KEY`

#####创建SSH KEY
- 1. ssh-keygen
- 2. SSH key文件保存在 ~/.ssh/xxx_id_rsa.pub
- 3. cat xxx_id_rsa.pub，复制内容到Git账号




##客服端&Demo
>[Git客服端](https://git-scm.com/downloads/guis) ：[`SourceTree`](https://www.sourcetreeapp.com/)

#####创建库
- 克隆服务库 
- 创建本地库
- 添加已存在的本地库

#####操作库 
- 提交
- 拉取	`先提交后拉取`
- 分支和标签 `创建分支` `切换分支` `合并分支` `拉取分支` `创建标签`
- 冲突 `避免冲突` `手动解决冲突` `使用我的版本解决冲突` `使用服务器版本解决冲突`
- 图表
- 回滚 `回滚行` `回滚工作目录` `回滚文件` `回滚提交`
- 贮藏


##SVN to Git
>[subgit](http://www.subgit.com/)

![svn convert git](https://github.com/mzying2013/GitShare/blob/master/svn-convert-git.png?raw=true)




##Jenkins
>[Jenkins](http://jenkins-ci.org/)是一个开源软件项目，旨在提供一个开放易用的软件平台，使软件的持续集成变成可能。