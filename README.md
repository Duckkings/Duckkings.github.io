# Duckkings.github.io

个人主页（GitHub Pages）。

## 如何更新作品

打开 `index.html`，搜索 `const PROJECTS = [`，在数组里增删项目即可：

- `title`：项目名
- `summary`：一句话概述
- `tags`：关键词（主页上可点击标签进入作品展示页）
- `links`：外链（GitHub / itch / bilibili / Gcores / docs 等）
- `bg`：作品展示页背景（作品网页截图；默认用 `thum.io` 第三方缩略图服务生成）
- `detail`：展示页要点（建议写：你做了什么 / 为什么这么做 / 结果如何）

作品展示页是 `p.html?id=<project-id>`。

## 计划中的增强（可选）

- 每个作品加封面图（`assets/`）
- 增加筛选（Boss/3C/武器/行为树/视频/文档）
- 增加中英双语切换
