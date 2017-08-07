![Git Logo](https://github.com/mzying2013/GitShare/blob/master/logo@2x.png?raw=true)


>Git是一款`免费`、`开源的`、`分布式版本`版本控制系统，用于敏捷高效地处理任何或小或大的项目。最初由`林纳斯·托瓦兹（Linus Torvalds）`创作。


- Linux
- Android
- JQuery
- PHP
- Git
- Ruby

![Github_logo](https://github.com/mzying2013/GitShare/blob/master/GitHub-Mark.png?raw=true)

![apple](https://github.com/mzying2013/GitShare/blob/master/apple_github.png?raw=true)

![google](https://github.com/mzying2013/GitShare/blob/master/google_github.png?raw=true)

<br/><br/><br/><br/><br/><br/>






## Git vs SVN

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

<br/><br/><br/><br/><br/><br/>





## Git关键词

- 工作区，暂存区，版本库。暂存区是为了原子性
  1. 分批、分阶段递交 
  2. 进行快照，便于回退


![三个区域图示](https://github.com/mzying2013/GitShare/blob/master/%E4%B8%89%E4%B8%AA%E5%8C%BA%E5%9F%9F%E5%9B%BE%E7%A4%BA.jpeg?raw=true)

<br/><br/><br/>





- 本地协议（Local），HTTP 协议，**SSH（Secure Shell）**协议及 Git 协议（最快，缺乏授权机制）


![ssh&git协议](https://github.com/mzying2013/GitShare/blob/master/ssh_http_proxy.png?raw=true)

<br/><br/><br/>





- 快照
  1. 变更文件的copy，而非diff。
  2. 查看版本直接load，不需要merge。空间换时间。
  3. .git文件会定期优化，保证快照空间和读取时间的平衡。


![差异化图示](https://github.com/mzying2013/GitShare/blob/master/%E5%B7%AE%E5%BC%82%E6%80%A7%E6%AF%94%E8%BE%83.png?raw=true)



![快照图示](https://github.com/mzying2013/GitShare/blob/master/%E5%BF%AB%E7%85%A7%E6%AF%94%E8%BE%83.png?raw=true)

<br/><br/><br/><br/><br/><br/>




## 服务端&Demo
> [GitLab](http://172.16.2.187/)

- 用户 `用户` `组`
- 库 `创建远程库`
- 协议 `http(s)://` **`ssh://`**（SSH KEY）



## 客服端&Demo
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


