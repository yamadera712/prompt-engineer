# AIプロンプトエンジニア

5つの構成要素を入力して、Claude や GPT に送信できる英文プロンプトを生成する Web アプリです。

🎯 **完全無料・永遠に使える** GitHub Pages ホスティング版

---

## ✨ 特徴

- 🎨 Apple モダンデザイン（ライト/ダークモード対応）
- 📋 5ステップのプロンプトビルダー
  - 役割設定（Role）
  - 命令指定（Task）
  - 出力形式（Format）
  - 制約設定（Constraints）
  - 連鎖思考（Chain of Thought）
- 🔄 リアルタイムプロンプト生成
- 📋 ワンクリックでコピー
- 🌙 自動ダークモード対応
- 📱 完全レスポンシブ（PC/iPad/iPhone対応）
- ⚡ インストール不要（ブラウザだけで動作）

---

## 🚀 使い方

ブラウザで開くだけ。インストール不要です！

### ステップバイステップ

1. **Step 1：役割を定義** - AI の思考の方向性を定めます
2. **Step 2：命令を指定** - 分析または実行する内容を詳しく説明
3. **Step 3：形式を選択** - 段落、Markdown、テーブル、コード（複数選択可）
4. **Step 4：制約を設定** - 文字数、トーン、避けるべき表現
5. **Step 5：思考を有効化** - ステップバイステップの推論を促す

最後に **「コピー」ボタン** → Claude / ChatGPT に paste して実行！

---

## 📦 ファイル構成

```
prompt-engineer/
├── index.html          # メインアプリケーション
├── README.md           # このファイル
├── .gitignore          # Git 無視設定
└── GitHub_Pages_Setup.md  # セットアップガイド（不要）
```

**重要：index.html だけで動作します。他のファイル不要！**

---

## 🛠️ 技術仕様

- **フロントエンド** - React 18（CDN 読み込み）
- **スタイル** - Tailwind CSS（CDN 読み込み）
- **アイコン** - SVG（インライン）
- **外部依存** - なし（CDN のみ）
- **ホスティング** - GitHub Pages（無料・永遠）

---

## 🌐 ホスティング情報

| 項目 | 説明 |
|------|------|
| **プロバイダー** | GitHub Pages（GitHub 公式ホスティング） |
| **料金** | 完全無料 |
| **制限** | なし |
| **削除リスク** | なし（GitHub アカウント有効な限り） |
| **HTTPS** | 対応 |
| **更新** | Git push で自動反映（数秒） |

---

## 🔄 更新方法

```bash
# index.html を編集
# → ファイルを保存

# GitHub にアップロード
git add index.html
git commit -m "Update app"
git push
```

数秒で本番環境に反映されます！

---

## 💡 トラブルシューティング

| 問題 | 解決策 |
|------|--------|
| **404 エラーが出る** | リポジトリが Public か確認 |
| **変更が反映されない** | キャッシュをクリア（Ctrl+Shift+Del） または 別ブラウザで確認 |
| **ダークモードが反映されない** | OS のダークモード設定を確認 |
| **コピーボタンが動かない** | HTTPS 対応ブラウザを使用 |

---

## 📱 シェア方法

公開 URL を以下の場所にシェア：

- 📧 メール
- 💬 Slack / Discord
- 🌍 X / Twitter
- 📌 ブックマーク
- 📱 iOS ホーム画面に追加（Safari の「共有」→「ホーム画面に追加」）

---

## 🎯 使用例

### マーケティング分析レポート作成
```
Role: マーケティング戦略コンサルタント
Task: Q4 の新製品ローンチ戦略を分析
Format: Markdown + Detailed Table
Tone: Professional
```

### 技術ドキュメント生成
```
Role: シニア エンジニア
Task: Python FastAPI の REST API 設計
Format: Code (JSON/Python)
Tone: Technical
Chain of Thought: 有効
```

---

## 🚀 今後の拡張案

- [ ] プロンプト保存機能（LocalStorage）
- [ ] テンプレート機能
- [ ] API 連携（Claude / OpenAI に直送信）
- [ ] 履歴機能
- [ ] エクスポート機能（JSON / Markdown）

---

## 📝 ライセンス

MIT License - 自由に使用・改変・配布できます

---

## 💬 フィードバック

- バグ報告 → Issue を作成
- 機能提案 → Discussions で提案
- 改善したい → Fork して Pull Request

---

## 🙏 謝辞

- **React** - UI フレームワーク
- **Tailwind CSS** - スタイリング
- **GitHub Pages** - ホスティング

---

**created with 💙 by バイブコーディング**
