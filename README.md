# CLAUDE 大補帖

> Claude Code 實用插件全攻略 — 賽博龐克像素風

一頁式網站，整理 Claude Code 最實用的插件與 Skills，方便在新機器安裝完 Claude Code 後快速查閱與設定。頂部標籤可切換「插件大補帖」與「HERDR 教學」兩個頁面。

## 插件大補帖

| # | 分類 | 插件 |
|---|------|------|
| 01 | 語言伺服器（LSP） | csharp-lsp、typescript-lsp、clangd-lsp、pyright-lsp |
| 02 | 瀏覽器自動化 | chrome-devtools-mcp、playwright |
| 03 | 知識查詢 | context7 |
| 04 | 工作流程強化 | superpowers、skill-creator |
| 05 | Matt Pocock Skills | /diagnose、/tdd、/grill-me 等 14 個斜線指令 |

## HERDR 教學

Herdr（agent 多工器，「coding agent 的 tmux」）精簡教學，章節子標籤切換：

| # | 章節 | 內容 |
|---|------|------|
| 01 | 認識 HERDR | 定位、牧羊人比喻、與 tmux / 桌面 App 比較表 |
| 02 | 安裝啟動 | 各平台安裝、啟動驗證、放第一隻 agent、更新 |
| 03 | 核心概念 | Session→Workspace→Tab→Pane→Agent 五層、客戶端/伺服器、五種狀態與彙整規則 |
| 04 | 指令速查 | Ctrl+B 快捷鍵表、常用 CLI、三種遠端模式、外掛市集 |

## 技術

- 純 HTML + CSS + 少量 vanilla JS（無框架、無建置流程）
- 部署於 Cloudflare Workers

## 部署

```bash
npx wrangler deploy
```

## 本地預覽

直接用瀏覽器開啟 `index.html` 即可。
