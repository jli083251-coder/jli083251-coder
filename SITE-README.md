# 学术个人主页

这是一个可直接用于 GitHub Pages 的轻量静态主页，使用原生 HTML 和 CSS 编写，无构建步骤、第三方库、JavaScript 或服务器端功能。

## 目录结构

- index.html：页面内容、个人资料、各模块模板和页面更新时间。
- assets/style.css：布局、颜色、排版和手机适配样式。

## 已从旧主页提取的信息

主页已填写你提供的姓名“李昂阳”、英文名“layy12”、邮箱 u202542343@xs.ustb.cn 和 2025 年 9 月入学时间。邮箱在首页顶部资料栏和 Contact 区各有一处。关于 AI、C++ 系统编程、算法和全栈项目的自述，以及两个公开项目仓库，是从你的 [GitHub 主页](https://github.com/jli083251-coder) 提取的。

主页还列出两个公开项目仓库：[Mei-AI-RMMV-Plugin](https://github.com/jli083251-coder/Mei-AI-RMMV-Plugin) 和 [RPGMV-Opera-Education-Game](https://github.com/jli083251-coder/RPGMV-Opera-Education-Game)。第二个仓库注明为团队作品，因此页面标记为 Team Project；目前不描述你的个人贡献。

主页目前不显示头像或个人照片。

## 目前留空的内容

打开 index.html，搜索 EDIT: 注释，可以找到要修改的位置：

- Google Scholar：目前没有主页，页面显示 No profile yet；建立后可在首页身份区添加链接。
- 头像 / 照片：当前不显示；以后可按需添加正式个人照片。
- 科研经历、实验室信息及个人贡献：目前不列出，之后可按真实经历添加。
- 奖项：目前不列出，之后可按实际情况添加。
- 研究兴趣：按你的真实关注方向调整 Research Interests 列表。
- 页面有实际内容更新时，修改底部的日期 2026-09-28。

网页中的学校、专业、姓名、邮箱和入学时间已经填写，无需再替换。

### 以后添加个人照片

把个人照片保存到 assets/，例如 assets/profile.jpg。然后在 index.html 的 profile-hero 区域添加 img 元素，指向该文件，并填写准确的 alt 文本。

### 增加科研经历或项目

Research Experience 模块当前只显示 No research experience listed yet.。以后有真实经历时，可在该区块中添加条目，填写实验室/项目名称、时间、导师、角色和个人贡献；不需要的部分继续留空即可。

Selected Projects 模块目前列出了两个旧主页中可核实的公开项目。复制带有 project-entry 样式类的条目即可增加项目；请填写项目链接、简短说明，并注明个人或团队项目以及你的实际贡献。

### 增加论文

目前 Publications 显示 “No publications yet.”。有论文后，在 index.html 的 Publications 模块中将这段文字替换为论文列表，建议填写作者、论文标题、会议/期刊、年份，并在有公开链接时附上 Paper 或 PDF 链接。只添加真实且可核实的论文。

Awards & Honors 模块当前只显示 No awards listed yet.。以后有奖项时，可把这行替换成奖项名称和年份。

## GitHub Pages 部署

主页文件已放在 `jli083251-coder/jli083251-coder` 仓库根目录中。该仓库不是 `jli083251-coder.github.io`，因此启用 Pages 后使用项目站点网址：

`https://jli083251-coder.github.io/jli083251-coder/`

在 GitHub 仓库中完成首次发布设置：

1. 打开 **Settings**。
2. 在 **Code, planning, and automation** 下打开 **Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**。
4. 选择 `main` 分支和 `/(root)` 目录，点击 **Save**。
5. 等待部署完成，再打开 Pages 设置页显示的网址。

此仓库原有的 `README.md` 是 GitHub 个人资料展示内容，已保留；本网站的维护说明文件为 `SITE-README.md`。

更多细节请参阅 [GitHub Pages 官方发布源配置说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)。

