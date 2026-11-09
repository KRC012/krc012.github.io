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

所有履历、学校、职位和项目均明确标记为待补充，不代表真实经历。GitHub 账户链接来自仓库 origin（KRC012），未加入邮箱。确认资料后再替换占位内容和页面标题、描述；没有作品链接时不要添加无效按钮。

## GitHub Pages

本次只完成本地开发，没有推送或启用发布。用户明确授权推送后，将页面提交到计划发布的分支，然后在仓库 Settings → Pages 中选择 Deploy from a branch、对应分支及 `/ (root)`。

当前 origin 为 `git@github.com:KRC012/kerunchen.github.io.git`。仓库名不匹配账户主页所需的 `KRC012.github.io` 命名；若保持现有名称且未配置自定义域名，应按项目站点使用 `https://krc012.github.io/kerunchen.github.io/`。所有本地资源采用相对路径，可兼容该子路径。实际发布地址以 GitHub Pages 设置为准。

## 可访问性与隐私

页面使用语义化章节、跳转正文链接、键盘焦点样式以及减少动态效果偏好。无外部字体、分析脚本、Cookie、表单或第三方资源请求；只有点击 GitHub 链接时才会跳转到外部站点。
