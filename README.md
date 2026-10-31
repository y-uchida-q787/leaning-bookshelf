# 学習本棚（learning-bookshelf）

学習に使う書籍を整理・管理するためのアプリケーションです。

## 現在のディレクトリ構成

現時点では、プロジェクトの方針とアイデアを整理するために必要なファイルだけを配置しています。

```text
learning-bookshelf/
├── docs/
│   ├── README.md
│   └── ideas.md
├── AGENTS.md
└── README.md
```

## 将来のディレクトリ構成

開発の進行に合わせて、次の構成へ拡張する予定です。現時点では、以下に記載した未使用のディレクトリやファイルは作成しません。

```text
learning-bookshelf/
├── apps/
│   ├── web/                 # ユーザー画面（React等）
│   ├── api/                 # バックエンド（Go等）
│   └── admin/               # 管理画面（Rails等）
│
├── docs/
│   ├── ideas.md             # 機能案・改善案・検討事項
│   ├── requirements/        # 要件定義
│   ├── design/              # 基本設計・詳細設計
│   ├── architecture/        # システム構成図
│   └── decisions/           # 技術選定・設計判断の記録
│
├── diagrams/
│   ├── er/                  # ER図
│   ├── uml/                 # UML
│   └── flows/               # 業務・画面フロー図
│
├── designs/
│   ├── wireframes/          # ワイヤーフレーム
│   └── assets/              # SVG等のデザイン素材
│
├── infra/                   # インフラ構成・設定
│
├── .github/
│   └── workflows/           # GitHub Actions
│
├── AGENTS.md                # AI向け開発ルール
├── README.md
└── .gitignore
```
