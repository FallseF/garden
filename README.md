# My Digital Garden

Personal digital garden built on [Quartz v5](https://quartz.jzhao.xyz).

公開先: https://fallsef.github.io/garden

## ローカル運用

```bash
# Obsidianで開く: ~/Diary/content/ を vault として開く

# ローカルプレビュー:
npx quartz build --serve

# 公開（v5ブランチへpush）:
npx quartz sync
```

## 構成

- `content/` — Obsidian vault（Markdown原稿）
- `content/diary/` — 日々の日記（`YYYY-MM-DD.md`）
- `quartz.config.yaml` — Quartz設定
- `.github/workflows/deploy.yml` — GitHub Pagesへの自動デプロイ

## Quartzアップデート

```bash
npx quartz update
```
