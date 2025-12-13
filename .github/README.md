# ドキュメント作成プロジェクト

## 📖 プロジェクト概要
日常のドキュメント作成とナレッジ管理を体系化するリポジトリ。AI対話で得た情報をマークダウンやMermaid図表で整理し、話題別・公開レベル別に管理する。

## 🚩 ナビゲーション
- [docs/index.md](docs/index.md): ルートインデックス（公開/非公開インデックスへのハブ）
- [docs/public/index.md](docs/public/index.md): 公開ドキュメント一覧
- [docs/private/index.md](docs/private/index.md): 非公開ドキュメント一覧（.gitignore 対象）
- [docs/templates/](docs/templates/): テンプレート置き場

## 📂 プロジェクト構造
```
docs/
├── public/
│   ├── ai-future/
│   ├── development/
│   └── github/
├── private/
│   ├── personal/
│   ├── pt-kankyo/
│   └── draft/
└── templates/
```

## 🔒 プライバシー・セキュリティ
- 公開情報は [docs/public/](docs/public/) 配下に格納。
- 個人情報・機密は [docs/private/](docs/private/) 配下に限定し、`.gitignore` で Git 追跡外。
- 下書きや検討中は draft 配下に置き、公開前に内容を精査。

## 🛠️ 作成・運用メモ
- マークダウンで構造化し、必要に応じてMermaidで図解。
- 公開レベルを明示し、インデックス ([docs/index.md](docs/index.md)) に追加する。
- 重要な更新時は [.github/copilot-instructions.md](.github/copilot-instructions.md) に反映する。

## 🆕 最近の更新
- （このファイルには更新履歴を掲載しません。各インデックスに記載しています）

## 🔧 技術スタック
- マークダウン: ドキュメント本体
- Mermaid: 図表・フローチャート・概念図
- GitHub: バージョン管理・公開管理
- VS Code + GitHub Copilot: 編集環境

## 📝 ドキュメント作成ガイドライン
- 明確なタイトルと構造化された見出し
- 適切なMermaid図表による視覚化
- 公開レベルの明確な分類
- 定期的な更新と改善
- 検索しやすいタグ付け