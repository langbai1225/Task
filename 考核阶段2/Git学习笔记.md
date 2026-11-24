# Git学习笔记
---
## hellow.md的上传流程
1. **克隆仓库**
- [x] git cione https://github.com.cnpmjs.org/langbai1225/Task.git


  cd 考核阶段2
2. **创建hello.md,写入内容**
- [x] echo "#Hello唐蔚杰">hello.md
3. **暂存，提交，推送**
- [x] git add hello.md

     git commit -m"add hellow.md"

     git push origin main
---
## Git作用：
- 本地版本控制工具，用来记录文件修改、随时回退，Git Bash是命令行操作终端。
## 仓库操作流程：
- 克隆仓库到本地 → 修改/新增文件 → 暂存 → 提交（commit）→ 推送到远程GitHub仓库。
​
## README与索引：
- README是仓库首页说明文件，用Markdown语法编写，可以做目录索引，添加链接、图片。
​
## 图片插入：
- 可以手动上传图片到仓库文件夹，复制Raw链接，用  ![描述](图片链接)  插入Markdown；PicGo可辅助图床上传，但国内网络访问GitHub容易失败。
---
  ## 你认为使用 Git Bash 提交麻烦吗？找一找，有没有更方便、更有效率的提交方式？
**有！！！！！！！**
- [x] 我认为用vs code更方便，更有效率 理由如下：
1. 图形化直观查看改动：左侧源代码管理面板，可以直接看到哪些文件改了、改了哪些行，不用敲命令查看差异，不容易搞错文件。
   ![说明](https://cdn.jsdelivr.net/gh/langbai1225/didactic-pancake@main/tuchang/713503809-72a02a98-45fb-48d9-8d9d-44ac624dd7f2.png)
2. 提交只需要用鼠标点commit就行了
3. 写代码和提交一体化：一边编辑Markdown、修改文件，一边就能提交，不用来回切换Git Bash窗口。
4. 预览方便，边写可以边看预览效果。
   ![说明](https://cdn.jsdelivr.net/gh/langbai1225/didactic-pancake@main/tuchang/713510049-9f8482a9-a49f-444f-8997-ba508aee7642.png)
5. 冲突可视化处理：遇到合并冲突时，VS Code会提供按钮选择保留哪一部分，比命令行手动删标记简单很多。
---
## 我的想法
1. **学习 Git 和 GitHub 之后，我认识到它不只是用来上传文件的工具，更是一套用于多人协作的版本管理规范。**
---
2. **刚开始使用时，Git Bash 的命令比较繁琐，容易出错，github.dev、VS Code 这类可视化工具会更加友好，适合新手。**
---
3. **团队仓库不能直接改动 main 主分支，所有修改都要新建分支、提交 PR，等待审核，以此保护仓库稳定。**
---
4. **Git 拥有版本回滚、冲突处理这类补救功能，提交出错后有办法挽回，但不同操作风险不一样，需要区分场景谨慎使用。**
---
5. **在学习过程中，我会把遇到的问题、报错和对应的解决方法记录下来，方便复盘，避免重复踩坑。**
## 一些感想
- [x] **使用 Git 最重要的是遵守协作规范，操作细心，坚持记录问题，循序渐进练习就能慢慢熟练。**
