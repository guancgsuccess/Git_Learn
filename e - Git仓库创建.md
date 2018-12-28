

# 创建仓库

#### 1. git init命令

可以使用任意一个目录作为git的仓库,比如目录名称为git_repo,通过cmd进入到该目录中执行

~~~
git init
~~~

Git 使用 **git init** 命令来初始化一个 Git 仓库，Git 的很多命令都需要在 Git 的仓库中运行，所以 **git init** 是使用 Git 的第一个命令。

`该命令执行完后会在当前目录生成一个 .git 目录`

#### 2. git clone命令

我们使用 **git clone** 从现有 Git 仓库中拷贝项目（类似 **svn checkout**）。 

克隆仓库的命令格式为：

~~~
git clone <repo>
~~~

如果我们需要克隆到指定的目录，可以使用以下命令格式：

~~~
git clone <repo> <directory>
~~~

**参数说明:**

* **repo:**Git 仓库。
* **directory:**本地目录。

