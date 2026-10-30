# Runzhuo Du · 个人主页

个人主页源文件，适用于 GitHub Pages。无须安装任何依赖或构建工具。

## 本地查看

双击 `index.html` 即可在浏览器打开。CSS、图标和交互脚本均包含在这个 HTML 文件中；页面不依赖外部字体、图片或第三方脚本。

## 页面内容

- 首页：姓名、学校、专业与个人介绍。
- 关于：简短介绍、兴趣爱好与 GitHub 链接。
- 研究兴趣：乳腺癌筛查、医学图像分析。
- 项目：三个已公开的 GitHub 仓库。
- 联系：邮箱与 GitHub 个人主页入口。

页面采用英文，姓名、专业、学校、研究兴趣、兴趣爱好与公开邮箱由本人提供。项目名称和简介来自公开 GitHub 仓库。未提供的经历、论文、奖项与头像未添加到页面；项目区可以按本人要求调整。

## GitHub Pages 发布

目标仓库：`maaaark-creator/maaaark-creator.github.io`

目标网站：<https://maaaark-creator.github.io/>

将本目录的 `index.html` 和 `.nojekyll` 放到仓库根目录，进入仓库的 **Settings → Pages**，选择 **Deploy from a branch → main → / (root)** 并保存。

`README.md` 和 `.gitignore` 可一同提交。不要上传父目录中的其他个人文件。

网站是否上线，以仓库 Pages 设置与实际访问结果为准。

## 修改内容

用文本编辑器打开 `index.html` 即可修改。发布后，更新这个文件并提交到同一仓库，网站便会重新部署。

页面包括手机布局、键盘焦点样式、移动导航、无 JavaScript 时的导航回退，以及减少动态效果的系统偏好支持。
