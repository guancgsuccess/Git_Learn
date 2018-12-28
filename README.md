

# 创建仓库

#### 1. git init命令

可以使用任意一个目录作为git的仓库,比如目录名称为git_repo,通过cmd进入到该目录中执行

```
git init
```

Git 使用 **git init** 命令来初始化一个 Git 仓库，Git 的很多命令都需要在 Git 的仓库中运行，所以 **git init** 是使用 Git 的第一个命令。

`该命令执行完后会在当前目录生成一个 .git 目录`

#### 2. git clone命令

我们使用 **git clone** 从现有 Git 仓库中拷贝项目（类似 **svn checkout**）。 

克隆仓库的命令格式为：

```
git clone <repo>
```

如果我们需要克隆到指定的目录，可以使用以下命令格式：

```
git clone <repo> <directory>
```

**参数说明:**

- **repo:**Git 仓库。
- **directory:**本地目录。

# Git简介

- Git是一个开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。
- Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。
- Git 与常用的版本控制工具 CVS, Subversion 等不同，它采用了分布式版本库的方式，不必服务器端软件支持。

## Git 与 SVN 区别

GIT不仅仅是个版本控制系统，它也是个内容管理系统(CMS),工作管理系统等。

如果你是一个具有使用SVN背景的人，你需要做一定的思想转换，来适应GIT提供的一些概念和特征。

- **GIT是分布式的，SVN不是**：这是GIT和其它非分布式的版本控制系统，例如SVN，CVS等，**最核心的区别**。
- GIT把内容按元数据方式存储，而SVN是按文件：所有的资源控制系统都是把文件的元信息隐藏在一个类似.svn,.cvs等的文件夹里。
- GIT分支和SVN的分支不同：分支在SVN中一点不特别，就是版本库中的另外的一个目录。
- GIT没有一个全局的版本号，而SVN有：目前为止这是跟SVN相比GIT缺少的最大的一个特征。
- GIT的内容完整性要优于SVN：GIT的内容存储使用的是SHA-1哈希算法。这能确保代码内容的完整性，确保在遇到磁盘故障和网络问题时降低对版本库的破坏。

## 快速入门

1. Git快速入门版本，你可以点击 [Git简明指南](http://www.runoob.com/manual/git-guide/) 查看。

2. Git 完整命令手册地址：<http://git-scm.com/docs>

   PDF 版命令手册：[github-git-cheat-sheet.pdf](http://www.runoob.com/manual/github-git-cheat-sheet.pdf)

3. [下载地址](https://gitforwindows.org/)

# 安装和配置

- [下载地址](https://gitforwindows.org/)

- 完成安装之后，就可以使用命令行的 git 工具（已经自带了 ssh 客户端）了，另外还有一个图形界面的 Git 项目管理工具。

  在开始菜单里找到"Git"->"Git Bash"，会弹出 Git 命令窗口，你可以在该窗口进行 Git 操作。

- 百度搜索git的环境变量的配置

- cmd进入输入

  ```
  git --version
  ```

  如果能够输出git的版本号,则表示安装成功
  
  # Git工作流

**一般工作流程如下：** 

- 克隆 Git 资源作为工作目录。
- 在克隆的资源上添加或修改文件。 
- 如果其他人修改了，你可以更新资源。
- 在提交前查看修改。
- 提交修改。
- 在修改完成后，如果发现错误，可以撤回提交并再次修改并提交。

**下图展示了Git工作流:**

![alt text](imgs/git-process.png)

​                                                 
