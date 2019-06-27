# 重学git
gitCommandStudy

#### git 三种状态

- 已提交（committed）: 表示数据已经安全的保存在本地数据库中
- 已修改（modified）: 表示修改了文件，但还没保存到数据库中
- 和已暂存（staged）: 表示对一个已修改文件的当前版本做了标记，使之包含在下次提交的快照中

### 指令列表

```js
git config [--global] --list // 输出git的全局配置列表 

git config --local --list // 输出git的本地配置列表 

git config --global user.name "John Doe" // 配置全局用户名

git config --global user.email johndoe@example.com // 配置全局邮箱


git config user.name "John Doe" // 配置本地用户名

git config user.email johndoe@example.com // 配置本地邮箱


```

### todo list

1. 创建一个git仓库，全局使用公司账号，本地使用github账号

