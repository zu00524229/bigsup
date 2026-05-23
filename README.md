# CLAUDE 大補帖

> Claude Code 實用插件全攻略 — 賽博龐克像素風

一頁式網站，整理 Claude Code 最實用的插件與 Skills，方便在新機器安裝完 Claude Code 後快速查閱與設定。

## 內容分類

| # | 分類 | 插件 |
|---|------|------|
| 01 | 語言伺服器（LSP） | csharp-lsp、typescript-lsp、clangd-lsp、pyright-lsp |
| 02 | 瀏覽器自動化 | chrome-devtools-mcp、playwright |
| 03 | 知識查詢 | context7 |
| 04 | 工作流程強化 | superpowers、skill-creator |
| 05 | Matt Pocock Skills | /diagnose、/tdd、/grill-me 等 14 個斜線指令 |

## 技術

- 純 HTML + CSS（無框架、無建置流程）
- 部署於 Cloudflare Workers

## 部署

```bash
npx wrangler deploy
```

## 本地預覽

直接用瀏覽器開啟 `index.html` 即可。
