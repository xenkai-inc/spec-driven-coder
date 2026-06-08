# <プロジェクト名>

<このアプリは何をするか、1行で>

> この README は **技術仕様** をまとめた入口です。
> 機能ごとの詳しい仕様は [`spec/`](spec/) ディレクトリにあります。

---

## 概要

### 解決したい課題
- <課題1>
- <課題2>

### 想定ユーザー
<誰が使うか>

---

## 技術スタック

- **フロントエンド**：Next.js (App Router) + TypeScript
- **スタイル**：Tailwind CSS
- **AI API**：Anthropic Claude API
- **デプロイ**：Vercel
- **テスト**：Vitest

---

## アーキテクチャ

<データの流れ・主要モジュールの関係を簡潔に。図や箇条書きで OK>

```
例）
ブラウザ (page.tsx)
  → API Route (app/api/chat/route.ts)  ※ APIキーはここで保持
  → Anthropic Claude API
```

---

## ディレクトリ構成

```
<プロジェクト名>/
├── README.md          # 技術仕様（このファイル）
├── spec/              # 機能ごとの仕様書
│   ├── index.md       # 仕様の目次
│   └── <機能>.md
├── src/
│   └── ...
└── tests/
    └── ...
```

---

## セットアップ

```bash
npm install
```

環境変数（必要な場合）：

```bash
# .env.local
ANTHROPIC_API_KEY=<your-key>
```

---

## 起動

```bash
npm run dev
```

---

## テスト

```bash
npm run test
```

---

## 仕様（spec/）

機能ごとの詳しい仕様は [`spec/`](spec/) にあります。
一覧は [`spec/index.md`](spec/index.md) を参照してください。
