1- 加入amend作为一项可以提升技术的命令

# 编辑 hello.py 和 main.py
git add hello.py
git commit

# 意识到你忘记添加 main.py 的更改
git add main.py
git commit --amend --no-edit