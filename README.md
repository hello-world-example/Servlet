# Servlet 


```
sed -i '' 's/Servlet/_NewProject_/g' `grep Servlet --include=\*.{md,html,xml,yaml} -rl .`

git config user.email ykb553@163.com
git config -l | grep user

# 更新主题模块
# git submodule add https://github.com/o-fork/hugo-book HuGo/themes/book
$ git submodule init
$ git submodule update

# 本地服务
hugo server -s HuGo/

# 生成静态站点
hugo -s HuGo/
```
