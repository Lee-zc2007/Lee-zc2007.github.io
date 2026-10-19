# 李泽诚的个人主页

纯 HTML + CSS，无需安装依赖。双击 index.html 即可在浏览器中查看。

## 文件说明
- index.html：个人信息、教育、项目、竞赛等内容。
- style.css：配色、排版与移动端适配。
- assets/resume-zh.pdf：中文简历。
- assets/resume-en.pdf：英文简历。

## 修改内容
1. 在 index.html 中搜索对应文字即可修改。
2. 照片：将照片保存为 assets/profile.jpg，再按 HTML 注释替换 monogram 区块。
3. 项目链接：目前未提供具体仓库地址，因此不添加虚构链接；有公开仓库后可在对应项目下加入链接。
4. 配色：修改 style.css 顶部的 --blue 变量。
5. 时间与在读状态按提供的简历保留，后续可直接修改。

## GitHub Pages
以简历中的 GitHub 用户名 Lee-zc2007 为例：
1. 创建仓库 Lee-zc2007.github.io（已有则使用该仓库）。
2. 将本文件夹内的 index.html、style.css 和 assets 文件夹上传至仓库根目录。
3. 仓库 Settings → Pages → Build and deployment，选择 Deploy from a branch。
4. 选择 main 分支与 / (root)，保存并等待部署完成。
5. 访问 https://Lee-zc2007.github.io/ 。

本次仅生成本地文件，未创建仓库或发布网站。两个 PDF 包含原简历中的电话等信息，随 assets 上传后可被访问；如需只展示网页，可移除 PDF 文件及对应的简历链接。

## 内容依据
以 SJTU-大二-李泽诚.pdf 为主要内容来源，参考英文简历核对技术术语。中文和英文简历个人荣誉存在差异，本页采用中文版本；未合并英文版本独有的综合测评专业第三信息。
未提供数学竞赛年份，页面使用横线表示。
布局参考 https://lliurunze.github.io/ 的个人简历式单页结构，页面样式独立编写。
