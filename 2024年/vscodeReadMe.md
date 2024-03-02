这是我试着用vscode做笔记的自用记录手册。
他其实不是一个非常适合用来做笔记的云笔记工具。作为笔记本有很高的学习成本
# 上传
1.下载并安装 Git： GitHub 使用 Git 作为其底层技术。

2.注册一个 GitHub 账户。

3.建立一个新的 GitHub 仓库。获取远程仓库的URL。

3.建立一个本地的 GitHub 仓库。

4.将本地仓库与远程仓库关联，使用以下命令：git remote add origin URL

5。在VSCode的顶部菜单中选择“终端(Terminal)” -> “新建终端(New Terminal)”来打开集成终端。

6.在终端中，输入git init 命令以初始化Git仓库

7.git branch -M main创建分支

8.添加文件到Git仓库.git add . 添加所有。git add 文件名添加指定文件。记得cd到所在目录

9.git commit -m "提交说明".

10.git push -u origin main 推送 main为所选分支

# 删除
网页可以直接删除，但不同步会导致后续上传报错。会保留历史记录。如果有需要可以清除历史
git pull --rebase origin main