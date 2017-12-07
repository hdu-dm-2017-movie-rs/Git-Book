- 初始化
  - $ git config --global user.name " "
  - $ git config --global user.email " "
  - $ git config --global color.ui auto

- 查看修改
  - $ ~/.gitconfig
  - $ git config --list

- 初始化仓库
  - $ mkdir 仓库名
  - $ cd 仓库名
  - $ git init

- 查看仓库状态+添加文件
  - $ git status
  - $ touch 文件名
  - $ git status    //文件显示在Untracked files
  - $ git add 文件名
  - $ git status
