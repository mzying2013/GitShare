![Git Logo](http://192.168.1.215:8088/raw/~liumin/GitShare.git/master/logo@2x.png)


>Git是一款`免费`、`开源的`、`分布式版本`控制系统，用于敏捷高效地处理任何或小或大的项目。最初由`林纳斯·托瓦兹（Linus Torvalds）`创作。



##Git vs SVN
- 分布式版本 `无需网络，完全独立`


- 分支 `Git的分支实际上仅是一个哈希值文件`


- 元数据存储 `SVN每个目录下都会有.SVN文件，Git只会在目录起点拥有一个.git目录`


- 内容完整性 `版本号是一个哈希值，哈希值是根据文件内容计算出来，所以在发生磁盘故障和网络问题的时候，可以根据版本号来确定文件内容完整性`


- 压缩传输 `Git压缩传输，SVN是一个一个文件传输`


- *无悲观锁 `无法锁定文件`*


![SVN vs Git](http://192.168.1.215:8088/raw/~liumin/GitShare.git/master/git-migration-centralized-vs-distributed.png)



##服务端&Demo
>GitBlit [`http://192.168.1.215:8088/`](http://192.168.1.215:8088/)

- 库
- 用户




##客服端&Demo
>[SourceTree](https://www.sourcetreeapp.com/)




##Jenkins
>[Jenkins](http://jenkins-ci.org/)是一个开源软件项目，旨在提供一个开放易用的软件平台，使软件的持续集成变成可能。