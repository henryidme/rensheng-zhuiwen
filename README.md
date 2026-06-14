# Henry Ai

这是一个 Obsidian + Quartz v5 的个人知识库站点，已准备部署到 Cloudflare Pages。

## 本地预览

```bash
npm ci
npx quartz plugin install
npx quartz build --serve
```

## Cloudflare Pages

创建 Pages 项目时使用这些设置：

- Framework preset: `None`
- Build command: `npx quartz plugin install && npx quartz build`
- Build output directory: `public`
- Node.js version: `22`

内容写在 `content/` 目录中。`private/`、`templates/` 和 `.obsidian/` 默认不会发布。
