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
