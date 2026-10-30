# Runzhuo Du · 个人主页

个人主页源文件，适用于 GitHub Pages。无须安装任何依赖或构建工具。

## 本地查看

双击 `index.html` 即可在浏览器打开。请将 `assets/` 文件夹与 HTML 保持在当前的相对位置。页面不依赖外部字体或第三方脚本。

页面采用白底、黑色顶栏、蓝色链接与衬线正文的学术主页风格，头像为本人提供的火箭插画。

## 页面内容

- 首页：姓名、学院、导师、头像与预计毕业年份（2028）。
- 关于：个人介绍、导师、Artificial Intelligence for Science 辅修（SIST）与 GitHub 链接。
- 研究兴趣：乳腺癌筛查、医学图像分析。
- 项目：结直肠病灶智能分割获奖项目、本人提供的流程图，以及两个已公开的 GitHub 仓库。项目区不显示编程语言标签。
- 教学与服务：Calculus 助教、2025–2026 学年学院学生发展委员会副主席。
- 联系：邮箱及国内外 PhD 或其他研究生项目的求学意向，申请兴趣为 cancer screening and diagnosis。

页面采用英文，个人资料、导师、辅修、教学与服务经历、竞赛获奖情况、求学意向、头像及项目流程图均由本人提供。获奖情况为：2026 年作为队长参加第十一届全国大学生生物医学工程创新设计竞赛并获得一等奖（前 5%）。两个已有仓库的名称和简介来自公开 GitHub 资料。未提供的论文与其他经历未添加到页面。

## GitHub Pages 发布

目标仓库：`maaaark-creator/maaaark-creator.github.io`

目标网站：<https://maaaark-creator.github.io/>

将本目录的 `index.html`、`.nojekyll` 和 `assets/` 文件夹放到仓库根目录，进入仓库的 **Settings → Pages**，选择 **Deploy from a branch → main → / (root)** 并保存。

`README.md` 和 `.gitignore` 可一同提交。不要上传父目录中的其他个人文件。

网站是否上线，以仓库 Pages 设置与实际访问结果为准。

## 修改内容

用文本编辑器打开 `index.html` 即可修改。头像保存在 `assets/avatar.png`，项目流程图保存在 `assets/colorectal-segmentation-workflow.png`。流程图可以点击查看原图。发布后，更新文件并提交到同一仓库，网站便会重新部署。

页面包括手机布局、键盘焦点样式与减少动态效果的系统偏好支持。导航和内容不依赖 JavaScript；脚本仅用于自动更新页脚年份。
