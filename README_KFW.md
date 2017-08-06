![Git Logo](https://github.com/mzying2013/GitShare/blob/master/logo@2x.png?raw=true)


>Git是一款`免费`、`开源的`、`分布式版本`版本控制系统，用于敏捷高效地处理任何或小或大的项目。最初由`林纳斯·托瓦兹（Linus Torvalds）`创作。


- Linux
- Android
- JQuery
- PHP
- Git
- Ruby
- ...



##Git vs SVN

![SVN vs Git](https://github.com/mzying2013/GitShare/blob/master/svn-vs-git.png?raw=true)

| SVN      | Git                |
| -------- | ------------------ |
| 中心仓库     | 分布式版本：离线仓库，离线日志，灵活 |
| 目录控制     | 分支&tag：指针          |
| .svn     | 元数据存储：.git         |
| 自增       | 内容完整性：版本号是哈希值      |
| 文件传输     | 压缩传输               |
| 无        | 重命名追踪              |
| 无        | 暂存区                |
| **可以锁定** | 无悲观锁（缺点）           |



## Git关键词

- 工作区，暂存区，版本库。暂存区是为了原子性：1. 一个是分批、分阶段递交 2. 一个是进行快照，便于回退
- ​






##服务端&Demo
> [GitLab](http://172.16.2.187/)

- 库 `创建远程库`
- 协议 `http(s)://` **`ssh://`**
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
- 拉取`先提交后拉取`
- 分支和标签 `创建分支` `切换分支` `合并分支` `拉取分支` `创建标签`
- 冲突 `避免冲突` `手动解决冲突` `使用我的版本解决冲突` `使用服务器版本解决冲突`
- 图表
- 回滚 `回滚行` `回滚工作目录` `回滚文件` `回滚提交`
- 贮藏


##SVN to Git
>[subgit](http://www.subgit.com/)

![svn convert git](https://github.com/mzying2013/GitShare/blob/master/svn-convert-git.png?raw=true)

