# git 教程

## git Basics
第一章就介绍完所有的常用的基础的命令

### Getting a Git Repository
1. git init
This creates a new subdirectory named .git that contains all of your necessary repository files – a Git repository skeleton. At this point, nothing in your project is tracked yet. 
会生成一个自动的代码库，这个代码库中间的git文件就是git core的内容

2. git add
这就是加上这个文件使得这个文件开始被track

3. git commit -m "commit content'
这个就是把追踪的文件提交到git中

4. git clone .git
这个是从一个git网上库下载到本地

### Recording Changes to the Repository
5. git status
可以看到当前add的文件和没有被add的文件
但是当被commit之后就不需要了

6. git diff
现在来阐述一下如何比较两个版本的文件
