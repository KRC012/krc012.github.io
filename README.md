# Personal Homepage

原生 HTML/CSS 个人主页，可直接用于 GitHub Pages；无需安装依赖或构建。

## 本地预览

在网站所在目录执行：

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

然后访问 http://127.0.0.1:8000 。

## 修改内容

- `index.html`：姓名、个人介绍、Experience、Education、Projects、Contact。
- `styles.css`：颜色、排版、桌面及移动布局。
- `assets/favicon.svg`：网站图标。

姓名、教育与工作经历依据本人提供的信息填写；不添加未经提供的职位、专业或项目成果。公司名称采用官网使用的英文品牌名：RealAI（https://www.realai.ai/about）与 Beta Infinity（https://betainf.com/），于 2026-11-09 核实。项目和个人邮箱暂未提供。GitHub 账户链接来自仓库 origin（KRC012），未加入公司邮箱；没有作品链接时不要添加无效按钮。

## GitHub Pages

发布配置：仓库 Settings → Pages → Deploy from a branch，选择 `main` 分支及 `/ (root)`。后续更新推送至 `main` 后，由 GitHub Pages 自动发布。

当前 origin 为 `git@github.com:KRC012/kerunchen.github.io.git`。仓库名不匹配账户主页所需的 `KRC012.github.io` 命名；若保持现有名称且未配置自定义域名，应按项目站点使用 `https://krc012.github.io/kerunchen.github.io/`。所有本地资源采用相对路径，可兼容该子路径。实际发布地址以 GitHub Pages 设置为准。

## 可访问性与隐私

页面使用语义化章节、跳转正文链接、键盘焦点样式，不使用动画。无外部字体、分析脚本、Cookie、表单或第三方资源请求；只有点击 GitHub 链接时才会跳转到外部站点。

Experience 使用公开记录中的英文全称：Beijing RealAI Intelligent Technology Co., Ltd.（[清华官方论坛议程](https://en.gff.pbcsf.tsinghua.edu.cn/en2023/info/1021/2037.htm)）和 Beijing Beta Infinity Intelligent Technology Co., Ltd.（[加拿大知识产权局商标记录](https://ised-isde.canada.ca/cipo/trademark-search/2474133)）。About 保留品牌简称。
