# Runzhuo Du · 个人主页

个人主页源文件，适用于 GitHub Pages。无须安装任何依赖或构建工具。

## 本地查看

双击 `index.html` 即可在浏览器打开。请将 `assets/avatar.png` 与 HTML 保持在当前的相对位置。页面不依赖外部字体或第三方脚本。

页面采用白底、黑色顶栏、蓝色链接与衬线正文的学术主页风格，头像为本人提供的火箭插画。

## 页面内容

- 首页：姓名、学校、专业、头像与预计毕业年份（2028）。
- 关于：简短介绍、兴趣爱好与 GitHub 链接。
- 研究兴趣：乳腺癌筛查、医学图像分析。
- 项目：三个已公开的 GitHub 仓库。
- 联系：邮箱与 GitHub 个人主页入口。

页面采用英文，姓名、专业、学校、研究兴趣、兴趣爱好、预计毕业年份、头像与公开邮箱由本人提供。项目名称和简介来自公开 GitHub 仓库。未提供的经历、论文与奖项未添加到页面；项目区可以按本人要求调整。

## GitHub Pages 发布

目标仓库：`maaaark-creator/maaaark-creator.github.io`

目标网站：<https://maaaark-creator.github.io/>

将本目录的 `index.html`、`.nojekyll` 和 `assets/` 文件夹放到仓库根目录，进入仓库的 **Settings → Pages**，选择 **Deploy from a branch → main → / (root)** 并保存。

`README.md` 和 `.gitignore` 可一同提交。不要上传父目录中的其他个人文件。

网站是否上线，以仓库 Pages 设置与实际访问结果为准。

## 修改内容

用文本编辑器打开 `index.html` 即可修改。头像保存在 `assets/avatar.png`。发布后，更新文件并提交到同一仓库，网站便会重新部署。

页面包括手机布局、键盘焦点样式与减少动态效果的系统偏好支持。导航和内容不依赖 JavaScript；脚本仅用于自动更新页脚年份。
